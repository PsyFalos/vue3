<script setup lang="ts">
import { useRouter } from 'vue-router'
const router = useRouter()
router.replace('/template-community') // 自动跳转到目标路由
</script>

<template>
  <div class="main-container flex">
  <div class="p-4 text-gray-400">正在跳转...</div>
  </div>
</template>
