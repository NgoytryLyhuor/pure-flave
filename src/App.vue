<script setup>
import { RouterLink, RouterView } from 'vue-router'
import NavBar from './components/Nav.vue';
import Footer from './components/Footer.vue';
</script>

<template>
  <NavBar/>
  <RouterView />
  <Footer/>
</template>

<style scoped>

</style>
