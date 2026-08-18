<script setup>
import Header from "./Header.vue";
import Button from "@/components/base/BaseButton.vue";
</script>

<template>
  <div
    class="w-full relative flex bg-cover bg-[url(@/assets/images/hero-bg.avif)] bg-top h-200"
  >
    <div class="flex flex-col w-full max-w-[1280px] mx-auto">
      <Header />
      <div
        class="flex flex-col w-full h-full items-center justify-center gap-8"
      >
        <h1 class="text-6xl w-[60%] text-center font-bold text-white">
          Tenha um site
          <span
            class="bg-linear-to-r from-[#9570E6] to-[#4F44FF] bg-clip-text text-transparent"
          >
            profissional
          </span>
          que gera vendas
        </h1>
        <p class="text-white font-light text-2xl w-[50%] text-center">
          Com um domínio de <span class="font-bold">alta performance</span> e
          focado em converter visitantes em compradores.
        </p>
        <button
          class="px-[56px] py-[16px] text-base border border-[#4F44FF] rounded-[16px] text-white bg-none"
        >
          Entrar em contato
        </button>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
