<script setup>
defineProps({
  image: {
    type: String,
    required: true,
  },
  alt: {
    type: String,
    default: "",
  },
  title: {
    type: String,
    default: "",
  },
  text: {
    type: String,
    default: "",
  },
});
</script>

<template>
  <div
    class="flex flex-col items-start w-full h-125 rounded-2xl overflow-hidden bg-[#ffffff]/2"
  >
    <img class="bg-cover w-full" :src="image" :alt="alt" />
    <div class="flex flex-col p-8 gap-4">
      <h3 class="text-white font-[500] text-[2rem] leading-8" :alt="alt">
        {{ title }}
      </h3>
      <p class="text-[#7C7986] font-[400] text-[1rem] text-balance" :alt="alt">
        {{ text }}
      </p>
    </div>
  </div>
</template>
