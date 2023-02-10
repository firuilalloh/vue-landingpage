<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <img class="fixed w-full bg-cover" src="./img/P3.jpg" alt="">
    <div>
      <nav class="absolute inset-y-0 w-full h-12 p-3 backdrop-blur-sm bg-white/30">
        <RouterLink class="px-2 font-semibold text-white uppercase hover:text-slate-300 hover:underline underline-offset-4 decoration-2" to="/">Home</RouterLink>
        <RouterLink class="px-2 font-semibold text-white uppercase hover:text-slate-300 hover:underline underline-offset-4 decoration-2" to="/team">Team</RouterLink>
        <RouterLink class="px-2 font-semibold text-white uppercase hover:text-slate-300 hover:underline underline-offset-4 decoration-2" to="/project">Project</RouterLink>
        <RouterLink class="px-2 font-semibold text-white uppercase hover:text-slate-300 hover:underline underline-offset-4 decoration-2" to="/about">About</RouterLink>
        <RouterLink class="px-2 font-semibold text-white uppercase hover:text-slate-300 hover:underline underline-offset-4 decoration-2" to="/contact">contact</RouterLink>
      </nav>
    </div>
  </header>

  <!-- <RouterView /> -->
</template>


