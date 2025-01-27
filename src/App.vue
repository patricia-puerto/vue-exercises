<script setup lang="ts">
import { RouterView } from 'vue-router'
import TheTitle from '@/components/TheTitle.vue'
import TheCounter from '@/components/TheCounter.vue'

const title = 'HERE IS THE PROPS TITLE'
</script>

<template>
  <section>
    <TheTitle :propTitle="title">
      <h3 class="slot">Here is the slot title</h3>
    </TheTitle>
    <TheCounter />
  </section>

  <RouterView />
</template>

<style scoped>
.slot {
  color: #34585f;
  margin-top: 0.4em;
  margin-left: 1em;
}
</style>
