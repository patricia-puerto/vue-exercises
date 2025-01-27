<script setup lang="ts">
import TheTitle from '@/components/TheTitle.vue'
import { ref } from 'vue'
const slot_title = 'Here is the counter title'
const counter = ref(0)
</script>
<template>
  <section>
    <TheTitle>
      <h4 class="slot">{{ slot_title }}</h4>
    </TheTitle>
    <button class="count-button" @click="counter++">Increment</button>
    <button class="count-button" @click="counter--">Decrement</button>
    <h3 class="counter">{{ counter }}</h3>
  </section>
</template>
<style scoped>
.count-button {
  margin-left: 1.8em;
  margin-top: 1em;
  background-color: #34585f;
  color: white;
  padding: 0.2em;
  border: none;
  font-size: 0.6em;
  border-radius: 0.3em;
  cursor: pointer;
}
.counter {
  margin-left: 4.2em;
  margin-top: 0.4em;
  color: #34221a;
}
.slot {
  margin-left: 1em;
}
</style>
