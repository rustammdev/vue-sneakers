<template>
  <header class="flex md:justify-between max-md:flex-col max-md:items-center max-md:gap-6 px-8 py-4 border-b border-slate-300">
    <div class="flex items-center gap-4">
      <img src="/logo.png" alt="logo" width="40" height="40" />
      <div>
        <h2 class="text-xl font-bold uppercase">Vue Snekers</h2>
        <p class="text-slate-700">Магазин лучших кроссовок</p>
      </div>
    </div>

    <ul class="flex gap-4">
      <li class="flex justify-center items-center gap-2">
        <img src="/cart.svg" alt="card" />
        <b class="text-slate-500 cursor-pointer hover:text-black">1205 руб.</b>
      </li>
      <li class="flex justify-center items-center gap-2">
        <img src="/heart.svg" alt="heart" />
        <span class="text-slate-500 cursor-pointer hover:text-black font-[600]"
          >Закладки</span
        >
      </li>
      <li class="flex justify-center items-center gap-2">
        <img src="/profile.svg" alt="heart" />
        <span class="text-slate-500 cursor-pointer hover:text-black font-[600]"
          >Профиль</span
        >
      </li>
    </ul>
  </header>
</template>
