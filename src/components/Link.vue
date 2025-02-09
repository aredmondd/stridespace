<script setup>
import { RouterLink } from 'vue-router';
const props = defineProps({
  link: String,
  route: String
});
</script>

<template>
  <RouterLink :to="route" class="font-inter hover:text-purple transition-colors duration-250 ease-in-out">{{ link }}</RouterLink>
</template>
