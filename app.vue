<script setup lang="ts">
const title: Ref<string> = ref('Hellow world');
</script>
<template>
  <div class="hello">
    <p>{{ title }}</p>
    <p>{{ runtimeConfig.public.test_env }}</p>
  </div>
</template>

<style scoped>
.hello {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 3rem;
  padding: 2rem;
}
</style>
