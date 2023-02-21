<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <img class="fixed w-full overflow-x-auto bg-cover" src="./img/P3.jpg" alt="">
    <div>
      <nav class="absolute inset-y-0 w-full h-12 p-3 backdrop-blur-sm">
        <RouterLink class="px-2 font-semibold text-white uppercase hover:text-slate-300 hover:underline underline-offset-4 decoration-2" to="/">Home</RouterLink>
        <RouterLink class="px-2 font-semibold text-white uppercase hover:text-slate-300 hover:underline underline-offset-4 decoration-2" to="/team">Team</RouterLink>
        <RouterLink class="px-2 font-semibold text-white uppercase hover:text-slate-300 hover:underline underline-offset-4 decoration-2" to="/project">Project</RouterLink>
        <RouterLink class="px-2 font-semibold text-white uppercase hover:text-slate-300 hover:underline underline-offset-4 decoration-2" to="/about">About</RouterLink>
        <RouterLink class="px-2 font-semibold text-white uppercase hover:text-slate-300 hover:underline underline-offset-4 decoration-2" to="/contact">contact</RouterLink>
      </nav>
      <RouterLink class="absolute h-10 px-4 py-1.5 font-semibold text-white rounded-full right-2 border border-white inset-y-1 hover:scale-105 duration-300" to="/login">Register</RouterLink>
      <RouterLink class="absolute h-10 px-4 py-1.5 font-semibold text-white rounded-full right-28  inset-y-1 hover:backdrop-blur-md duration-300" to="/signin">Sign In</RouterLink>
    </div>
  </header>

  <RouterView />
</template>


