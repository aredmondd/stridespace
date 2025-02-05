<script setup>
import { RouterLink } from 'vue-router';
</script>

<template>
    <div class="flex justify-between items-center mt-3 mx-3">
        <RouterLink to="/" class="text-white font-martian-mono text-4xl">STRIDESPACE</RouterLink>
        <div class="flex justify-between gap-4">
            <RouterLink to="/about" class="font-albert-sans hover:text-purple transition-colors duration-250 ease-in-out">about</RouterLink>
            <RouterLink to="/pricing" class="font-albert-sans hover:text-purple transition-colors duration-250 ease-in-out">pricing</RouterLink>
            <RouterLink to="/login" class="font-albert-sans hover:text-purple transition-colors duration-250 ease-in-out">login</RouterLink>
        </div>
    </div>
    
</template>