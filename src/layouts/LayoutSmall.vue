<script setup>
import SmallFooter from '@/components/templates/small/SmallFooter.vue'
import SmallHeader from '@/components/templates/small/SmallHeader.vue'
</script>

<template>
  <header>
    <small-header />
  </header>
  <main>
    <router-view />
  </main>
  <footer>
    <small-footer />
  </footer>
</template>
