<script setup lang="ts">
import { defineProps } from 'vue';
defineProps({
  propTitle: String,
});
const title = 'Here is THE TITLE';
</script>
<template>
  <h2 class="title">{{ title }}</h2>
  <h3 class="props">{{ propTitle }}</h3>
  <slot></slot>
</template>
<style scoped>
.title {
  color: #876150;
  margin-top: 0.5em;
  margin-left: 1em;
}
.props {
  color: #5f4134;
  margin-top: 0.3em;
  margin-left: 1em;
}
</style>
