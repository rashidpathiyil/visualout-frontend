<template>
  <div
    flex
    justify-between
    items-center
    mx-5 lg:px-20
  >
    <div flex items-center>
      <Logos />
    </div>
    <div
      items-center
      text="xl gray4"
      m-5
      flex
      justify-center
      gap-3
    >
      <NuxtLink i-carbon-home to="/" />
      <a i-carbon-logo-github href="https://github.com/rashidpathiyil" target="_blank" />
      <!-- <DarkToggle /> -->
    </div>
  </div>
</template>
