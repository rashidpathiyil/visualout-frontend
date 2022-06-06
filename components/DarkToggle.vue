<script setup lang="ts">
const color = useColorMode()

function toggleDark() {
  color.preference = color.value === 'dark' ? 'light' : 'light' // temporary disable by setting "light"
}
</script>

<template>
  <button class="!outline-none" @click="toggleDark">
    <div class="dark:i-carbon-moon i-carbon-sun" />
  </button>
</template>
