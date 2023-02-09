<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <img class="w-full bg-cover" src="./img/P3.jpg" alt="">
    <div>
      <nav class="absolute inset-y-0 w-full h-12 p-3  backdrop-blur-sm bg-white/30">
        <RouterLink class="px-2 font-semibold text-white uppercase hover:text-slate-300" to="/">Home</RouterLink>
        <RouterLink class="px-2 font-semibold text-white uppercase hover:text-slate-300" to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <!-- <RouterView /> -->
</template>


