<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>  
    <header class="flex justify-between border-b border-slate-200 px-10 ">
    <div class="flex items-center gap-4">
      <img src="" alt="Logo" class="w-11" />
      <div>
        <h2 class="font-bold text-xl uppercase">REACT SNEAKERS</h2>
        <p class="text-slate-400">магазин лучших кроссовок</p>
      </div>
    </div>

    <ul class="flex items-center gap-10">
      <li class="flex items-center gap-3 cursor-pointer">
        <img src="" alt="Cart" />
        <b>1205 рубл </b>
      </li>
      <li class="flex items-center gap-3 cursor-pointer">
        <img src="/heart.svg" alt="Favorite" />
        <span>Закладки</span>
      </li>
      <li class="flex items-center gap-3 cursor-pointer">
        <img src="/profile.svg" alt="Favorite" />
        <span>Профиль</span>
      </li>
    </ul>
  </header>
  </header>
  <h1 class="text-3xl font-bold underline">
    Hello world!
  </h1>
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>


  <RouterView />
</template>

<style scoped>

</style>
