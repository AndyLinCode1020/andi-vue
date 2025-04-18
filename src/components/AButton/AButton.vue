<template>
  <button
    :class="[
      'px-4 py-2 rounded text-white',
      type === 'primary' ? 'bg-(--primary-color)' : 'bg-gray-500',
      disabled && 'opacity-50 cursor-not-allowed',
    ]"
    :disabled="disabled"
  >
    {{ label }}
  </button>
</template>

<script setup lang="ts">
defineProps<{
  label: string;
  type?: 'default' | 'primary';
  disabled?: boolean;
}>();
</script>
