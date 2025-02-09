<template>
    <div class="flex items-center gap-4 justify-center h-screen bg-black">
      <span 
        v-for="(char, index) in text" 
        :key="index" 
        class="breathe-text font-martian-mono text-purple uppercase text-5xl" 
        :style="{ animationDelay: `${index * 0.3}s` }"
      >
        {{ char }}
      </span>
    </div>
  </template>
  
  <script setup>
  import { ref } from "vue";
  
  const text = ref("get started today?"); // Change this to any word
  </script>
  
  <style>
  .breathe-text {
    animation: letter-breathe 3s ease-in-out infinite;
  }
  
  @keyframes letter-breathe {
    from, to {
      font-variation-settings: 'wght' 100;
    }
    50% {
      font-variation-settings: 'wght' 900;
    }
  }
  </style>  