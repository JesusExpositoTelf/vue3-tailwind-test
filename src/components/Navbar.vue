<template>
<nav class="bg-white shadow">
  <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
    <div class="flex h-16 justify-between">
      <div class="flex flex-shrink-0 items-center">
        <RouterLink :to="{name: 'inicio'}">
          <img class="h-8 w-auto" src="@/assets/logo.svg" alt="Your Company" />
        </RouterLink>
      </div>
      <button>
        <img src="@/assets/bag.svg" alt="Cart" class="h-8 w-8" />
      </button>
    </div>
  </div>
</nav>
</template>

<script setup lang="ts">

</script>

<style scoped>

</style>