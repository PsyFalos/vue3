<script setup lang="ts">
import { useRouter } from 'vue-router'
const router = useRouter()
router.replace('/recent-formulas') // 自动跳转到目标路由
</script>

<template>
  <Logos my="4" />
  <HelloWorld msg="Hello Vue 3 + Element Plus + Vite" />
  <div class="p-4 text-gray-400">正在跳转...</div>
</template>
