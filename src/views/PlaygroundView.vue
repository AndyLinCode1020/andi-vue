<template>
  <div class="p-8 space-y-8">
    <h1 class="text-2xl font-bold">🎮 Playground - 測試元件</h1>

    <!-- 測試 MyButton -->
    <section class="space-y-4">
      <h2 class="text-xl font-semibold">🧪 MyButton 測試</h2>
      <div class="flex gap-4 items-center">
        <a-button label="預設按鈕" />
        <a-button label="禁用狀態" :disabled="true" />
        <a-button label="主題色" type="primary" />
      </div>
    </section>

    <!-- 可以新增更多元件測試區塊 -->
  </div>
</template>

<script setup lang="ts">
import AButton from '@/components/AButton/AButton.vue';
</script>
