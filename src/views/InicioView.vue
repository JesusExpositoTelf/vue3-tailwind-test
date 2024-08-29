<template>
  <Navbar />
  <div class="mx-auto px-4 py-16 sm:px-6 sm:py-24 lg:max-w-7xl lg:px-8">
    <div class="mt-6 grid gap-x-6 gap-y-10 grid-cols-4 ">
      <LibroCard />
      <LibroCard />
      <LibroCard />
      <LibroCard />
      <LibroCard />
      <LibroCard />
      <LibroCard />
      <LibroCard />
      <LibroCard />
      <LibroCard />
      <LibroCard />
      <LibroCard />
    </div>
  </div>
</template>

<script setup lang="ts">

import LibroCard from "@/components/LibroCard.vue";
import Navbar from "@/components/Navbar.vue";
</script>

<style scoped>

</style>