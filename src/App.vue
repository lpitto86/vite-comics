<script setup>
import AppHeader from './components/AppHeader.vue'
import AppJumbotron from './components/AppJumbotron.vue'
import AppCards from './components/AppCards.vue'
import AppFooter from './components/AppFooter.vue'
</script>

<template>
  <header>
    <AppHeader/>
  </header>

  <main>
    <AppJumbotron/>
    <AppCards/>
  </main>

  <footer>
    <AppFooter/>
  </footer>
</template>

<style scoped>
</style>