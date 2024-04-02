<script setup>
import LargeAside from '@/components/templates/large/LargeAside.vue'
import LargeFooter from '@/components/templates/large/LargeFooter.vue'
import LargeHeader from '@/components/templates/large/LargeHeader.vue'
</script>

<template>
  <header>
    <large-header />
  </header>
  <aside>
    <large-aside />
  </aside>
  <main>
    <router-view />
  </main>
  <footer>
    <large-footer />
  </footer>
</template>
