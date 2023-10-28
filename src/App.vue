<template>
  <HelloWorld>
    <template #header>
      <div>lqnhat header</div>
    </template>
    <template #default="{age}">
      <h1>Yêu em Trang meo</h1>
    </template>
    <template #footer>
      <div>lqnhat footer commit</div>
    </template>
  </HelloWorld>
</template>

<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue';
</script>

<style scoped>
</style>
