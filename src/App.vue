<script setup>
import { RouterLink, RouterView } from 'vue-router'
import TheFooter from './components/TheFooter.vue';
import TheNav from './components/TheNav.vue';
</script>

<template>

  <header class="text-center">
    <TheNav/>
    <nav class="p-4 text-2xl text-blue-700">
      <RouterLink to="/" class="p-10">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
    </nav>
  </header>

  <TheFooter/>
  <RouterView/>
</template>

<style scoped>
</style>
