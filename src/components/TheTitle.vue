<script setup lang="ts">
import { defineProps } from 'vue';
defineProps({
  propTitle: String,
});
</script>
<template>
  <h2 class="title">Here is THE TITLE</h2>
  <h3 class="props">{{ propTitle }}</h3>
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
