<template>
  <Navigation />
  <RouterView />
  <Footer />
</template>

<style scoped>

</style>

<script setup>
import { RouterView } from 'vue-router'
import Navigation from './components/HelloWorld.vue'
import Footer from './components/navigation.vue'
</script>
