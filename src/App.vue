<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue';
</script>

<template>
  <header>
    <Navbar />
    <div class="wrapper">
    </div>
  </header>

  <RouterView />
</template>
