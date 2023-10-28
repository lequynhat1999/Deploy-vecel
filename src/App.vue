<template>
  <HelloWorld>
    <template #header>
      <div>lqnhat header</div>
    </template>
    <template #default="{age}">
      lqnhat not override {{ age }}
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
