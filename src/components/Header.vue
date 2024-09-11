<template>
  <header class="flex justify-between border-b border-slate-300 px-10 py-8">
    <div class="flex items-center gap-4">
      <img src="/logo.png" alt="logo" class="w-10 mr-5" />
      <div>
        <h2 class="text-xl font-bold uppercase">Vue Sneakers</h2>
        <p class="text-slate-500">Магазин лучших кроссовок</p>
      </div>
    </div>
    <ul class="flex items-center gap-10 text-slate-500">
      <li class="flex cursor-pointer items-center gap-3 hover:text-slate-800">
        <img src="/cart.svg" alt="Cart" />
        <span>1205 руб.</span>
      </li>
      <li class="flex cursor-pointer items-center gap-3 hover:text-slate-800">
        <img src="/heart.svg" alt="Heart" />
        <span>Закладки</span>
      </li>
      <li class="flex cursor-pointer items-center gap-3 hover:text-slate-800">
        <img src="/profile.svg" alt="Profile" />
        <span>Профиль</span>
      </li>
    </ul>
  </header>
</template>
