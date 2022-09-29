<script setup lang="ts">
defineProps<{
  n: number;
  content: string;
  url: string;
}>();
</script>

<template>
  <div>
    <a :href="url">
      <small class="text-xs text-gray-700">[{{ n }}] {{ content }}</small>
    </a>
  </div>
</template>
