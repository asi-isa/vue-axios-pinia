<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <div class="h-screen flex flex-col gap-10 items-center py-5">
    <header class="flex gap-3 text-lg">
      <RouterLink :to="{ name: 'home' }">Home</RouterLink>
      <RouterLink :to="{ name: 'about' }">About</RouterLink>
    </header>

    <RouterView />
  </div>
</template>
