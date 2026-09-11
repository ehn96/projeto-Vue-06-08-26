<script setup>
import Card from "@/components/layout/Card.vue";
import card1 from "@/assets/images/cards/card1.avif";
import card2 from "@/assets/images/cards/card2.avif";
import card3 from "@/assets/images/cards/card3.avif";
</script>

<template>
  <div
    class="flex w-full h-250 bg-[url(@/assets/images/bg-secao2.avif)] bg-cover relative py-[100px]"
  >
    <div class="flex flex-col w-[1920px] gap-20 max-w-[1280px] mx-auto">
      <h2 class="mx-auto text-white text-[3rem] italic font-[400]">
        Porque ter um site nos dias de hoje?
      </h2>
      <div class="flex flex-row w-full justify-between gap-[50px]">
        <Card
          :image="card1"
          title="Vitrine Online"
          text="Todo empreendedor que deseja se destacar precisa de um site para expor seus produtos e serviços de forma clara e objetiva. Um site estratégico funciona como um guia para o cliente; nele, você controla 100% do conteúdo e converte cliques em vendas."
        />
        <Card
          :image="card2"
          title="Autoridade e Confiança"
          text="As redes sociais são terrenos alugados; um site é sua sede própria. Ter um endereço oficial na web passa a segurança que o “link na bio” não consegue entregar sozinho."
        />
        <Card
          :image="card3"
          title="Seja Encontrado"
          text="Onde o seu cliente te procura, você aparece? 90% das buscas acontecem no Google. Quem domina as primeiras posições fica com os lucros; quem não aparece, perde para a concorrência."
        />
      </div>
    </div>
  </div>
</template>
