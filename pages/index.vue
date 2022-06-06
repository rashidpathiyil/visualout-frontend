<template>
  <div class="background">
    <Suspense>
      <template #fallback>
        <div op50 italic>
          <span animate-pulse>Loading...</span>
        </div>
      </template>
    </Suspense>
    <section mx-5 lg:mx-20 flex items-center h-full>
      <div>
        <h1 text-6xl font-bold>
          We build Custom Apps
        </h1>
        <p mt-6>
          We are team of passionate developers who build high quality websites and apps
        </p>
        <InputEntry />
      </div>
    </section>
  </div>
</template>

<style scoped>
  .background {
    background-image: url('/visualout-backkground.jpg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    height: 100vh;
  }
</style>
