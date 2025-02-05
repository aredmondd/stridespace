<script setup>
import { RouterLink } from 'vue-router';
</script>

<template>
    <div class="flex justify-between items-center mt-3 mx-6">
        <RouterLink to="/" class="text-white font-martian-mono text-4xl">STRIDESPACE</RouterLink>
        <div class="flex justify-between gap-4">
            <RouterLink to="/about" class="font-albert-sans">about</RouterLink>
            <RouterLink to="/" class="font-albert-sans">pricing</RouterLink>
            <RouterLink to="/" class="font-albert-sans">login</RouterLink>
        </div>
    </div>
</template>