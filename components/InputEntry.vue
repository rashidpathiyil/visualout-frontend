<script setup lang="ts">
const name = ref('')

const router = useRouter()
const go = () => {
  if (name.value)
    router.push(`/hi/${encodeURIComponent(name.value)}`)
}
</script>

<template>
  <div>
    <input
      id="input"
      v-model="name"
      class="placeholder-light-50"
      placeholder="What's your name?"
      type="text" autocomplete="off"
      p="x-4 y-2" m="t-5" w="250px"
      text="center" bg="transparent"
      border="~ rounded gray-900 dark:gray"
      outline="none active:none"
      @keydown.enter="go"
    >
    <div>
      <button
        mt-3 text-sm btn
        :disabled="!name"
        @click="go"
      >
        GO
      </button>
    </div>
  </div>
</template>
