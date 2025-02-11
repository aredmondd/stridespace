<script setup>
import Hero from '@/components/Hero.vue';
import BreathingText from '@/components/BreathingText.vue';
import { RouterLink } from 'vue-router';
import Features from '@/components/Features.vue';
import ContentScroller from '@/components/ContentScroller.vue';
</script>

<template>
    <main class="flex flex-col flex-1">
        <div class="flex justify-center items-center mt-24">
            <div class="flex flex-col">
                <Hero />
            </div>
        </div>

        <Features />

        <ContentScroller/>

        <div class="flex flex-col gap-4 items-center justify-center mt-24 mx-12 mb-32">
            <div class="p-2 mt-6">
                <h1 class="font-martian-mono text-4xl opacity-75">get started today</h1>
            </div>
            <div class="flex gap-12">
                <RouterLink to="/signup" class="font-martian-mono text-2xl p-2 bg-purple text-black text-left hover:bg-white hover:text-black transition-all duration-500 ease-in-out">signup</RouterLink>
                <RouterLink to="/login" class="font-martian-mono text-2xl p-2 bg-purple text-black text-left hover:bg-white hover:text-black transition-all duration-500 ease-in-out">login</RouterLink>
            </div>
        </div>
    </main>
</template>
