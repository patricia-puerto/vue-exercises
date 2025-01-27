<script setup lang="ts">
import { RouterView } from 'vue-router'
import TheTitle from '@/components/TheTitle.vue'
</script>

<template>
  <header>
    <div>
      <h1>You did it!</h1>
    </div>
  </header>
  <section>
    <TheTitle />
  </section>

  <RouterView />
</template>

<style scoped></style>
