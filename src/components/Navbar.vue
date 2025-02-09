<script setup>
import Link from './Link.vue';
import { RouterLink } from 'vue-router';
</script>
  
<template>
    <div class="flex justify-between items-center mt-3">
        <RouterLink to="/" class="text-white font-martian-mono text-4xl">STRIDESPACE</RouterLink>
    <div class="flex justify-between gap-4">
        <Link :link="'about'" :route="'/about'" />
        <Link :link="'pricing'" :route="'/pricing'" />
        <Link :link="'login'" :route="'/login'" />
    </div>
    </div>
</template>