<script setup lang="ts">
const { t } = useI18n()
const router = useRouter()
</script>

<template>
  <main p="x4 y10" text="center teal-700 dark:gray-200">
    <div text-4xl>
      <div i-carbon-warning inline-block />
    </div>
    <div>
      404 Not Found
    </div>
    <div>
      <button text-sm btn m="3 t8" @click="router.back()">
        返回
      </button>
    </div>
  </main>
</template>

<route lang="yaml">
meta:
  layout: 404
</route>
