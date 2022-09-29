<template>
  <footer v-if="$slidev.nav.currentLayout !== 'cover'">
    <div class="absolute bottom-0 left-0 p-2 text-teal-600">
      {{ $slidev.configs.title }}
    </div>

    <div class="absolute bottom-0 right-0 p-2 text-teal-600">
      {{ $slidev.nav.currentPage }} / {{ $slidev.nav.total }}
    </div>
  </footer>
</template>
