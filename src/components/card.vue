<script setup>
defineProps({
  title: String,
  imageUrl: String,
  price: Number,
});
</script>

<template>
  <div
    class="w-[260px] h-[310px] border border-[#F3F3F3] shadow-sm hover:shadow-md hover:translate-y-[-5px] transition relative rounded-[45px] flex justify-center items-center flex-col"
  >
    <div class="w-[80%] h-[80%]">
      <img
        :src="!isFavorite ? '/like-1.svg' : '/like-2.svg'"
        alt="plus"
        class="absolute top-8 cursor-pointer"
      />
      <img :src="imageUrl" alt="snkeakers" class="w-[170px] h-auto m-auto" />

      <h2 class="text-[16px] font-[600] mt-2">
        {{ title }}
      </h2>
      <div class="flex justify-between mt-2">
        <div class="">
          <p class="text-[14px] text-[#BDBDBD] uppercase">Цена:</p>
          <span class="font-bold text-[18px] leading-none"
            >{{ price }} руб.</span
          >
        </div>

        <img
          :src="isAdded ? console.log('yes')
           : console.log('no')"
          width="32"
          height="32"
          alt="plus"
          class="cursor-pointer"
        />
      </div>
    </div>
  </div>
</template>
