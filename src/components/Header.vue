<template>
    <header class="flex justify-between border-b border-slate-200 px-10">
    <div class="flex items-center gap-4">
      <img src="../assets/logo.svg" alt="Logo" class="w-11" />
      <div>
        <h2 class="font-bold text-xl uppercase">REACT SNEAKERS</h2>
        <p class="text-slate-400">магазин лучших кроссовок</p>
      </div>
    </div>

    <ul class="flex items-center gap-10">
      <li class="flex items-center gap-3 cursor-pointer">
        <img src="../assets/cart-icon.svg" alt="Cart" />
        <b>1205 рубл </b>
      </li>
      <li class="flex items-center gap-3 cursor-pointer">
        <!-- <img src="/heart.svg" alt="Favorite" /> -->
        <span>Закладки</span>
      </li>
      <li class="flex items-center gap-3 cursor-pointer">
        <!-- <img src="/profile.svg" alt="Favorite" /> -->
        <span>Профиль</span>
      </li>
    </ul>
    </header>
</template>