<script setup>
import { RouterLink } from 'vue-router';
import Link from './Link.vue';
</script>

<template>
    <div class="flex justify-between items-center">
        <RouterLink to="/" class="text-white font-martian-mono text-6xl">SS</RouterLink>
        <div class="flex flex-col justify-between items-end gap-4">
            <div class="flex gap-4">
                <Link :link="'about'" :route="'/about'" />
                <Link :link="'pricing'" :route="'/pricing'" />
                <Link :link="'login'" :route="'/login'" />
                <Link :link="'signup'" :route="'/signup'" />
                <a href="https://github.com/aredmondd/stridespace" target="_blank" class="font-inter hover:text-purple transition-colors duration-250 ease-in-out">source code</a>
            </div>
            <p class="text-white opacity-25 font-martian-mono">all aspects of this website were designed and implemented by aiden redmond</p>
        </div>
    </div>
</template>