<script setup lang="ts">
import { RouterView } from 'vue-router'
import ExampleComponent from '@/components/ExampleComponent.vue'
</script>

<template>
  <header>
    <div>
      <h1>You did it!</h1>
    </div>
  </header>
  <section>
    <ExampleComponent />
  </section>

  <RouterView />
</template>

<style scoped></style>
