<script setup lang="ts">
defineProps<{
  n: number;
  title: string;
  src: string;
}>();
</script>

<template>
  <div class="grid justify-items-center">
    <img class="w-full" :src="src" />
    <span class="mt-2 item-center text-sm text-gray-700"
      >図{{ n }}: {{ title }}</span
    >
  </div>
</template>
