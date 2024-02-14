<script setup>
import Card from "./card.vue";
</script>

<template>
  <!-- Card section -->
  <div class="mt-6">
    <h1 class="font-bold text-2xl">Все кроссовки</h1>
    <div
      class="flex flex-wrap justify-around gap-x-2 gap-y-4 items-center mt-6"
    >
      <Card
        title="Мужские Кроссовки Nike Blazer Mid Suede"
        imageUrl="/sneakers/sneakers-1.jpg"
        :price="2700"
        is-added= "true"
      />
      
    </div>
  </div>
  <!-- Card section end -->
</template>
