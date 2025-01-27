<script setup lang="ts">
import { RouterView } from 'vue-router'
import TheTitle from '@/components/TheTitle.vue'

const title = 'HERE IS THE PROPS TITLE'
</script>

<template>
  <header>
    <div>
      <h1>You did it!</h1>
    </div>
  </header>
  <section>
    <TheTitle :propTitle="title" />
  </section>

  <RouterView />
</template>

<style scoped></style>
