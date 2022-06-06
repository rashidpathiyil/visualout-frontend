<script setup>
useHead({
  title: 'Visualout',
  link: [
    {
      rel: 'icon', type: 'image/svg', href: '/visualout.svg',
    },
  ],
})
</script>

<template>
  <NuxtLayout cl>
    <NuxtPage />
  </NuxtLayout>
</template>

<style>
html, body , #__nuxt{
  height: 100vh;
  margin: 0;
  padding: 0;
}

html.dark {
  background: #0067dc;
  color: white;
}
</style>
