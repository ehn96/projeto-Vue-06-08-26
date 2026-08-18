<script setup>
import BaseButton from "@/components/base/BaseButton.vue";
import SecTitle from "@/components/Text/SectionTitle.vue";
</script>

<template>
  <div
    class="flex flex-row w-full place-content-between h-20 max-w-[1280px] items-center"
  >
    <img src="@/assets/icons/logo.png" class="w-16 h-16" />
    <div class="flex flex-row gap-[42px]">
      <SecTitle>Serviços</SecTitle>
      <SecTitle>Sobre</SecTitle>
      <SecTitle>Diferenciais</SecTitle>
      <SecTitle>Dúvidas</SecTitle>
      <SecTitle>Contato</SecTitle>
    </div>

    <BaseButton>Fale comigo</BaseButton>
  </div>
</template>

<style scoped></style>
