<template>
    <div class="relative flex items-center justify-center h-screen bg-black overflow-hidden py-12">
        <!-- Grid Overlay -->
        <div class="absolute inset-0 bg-grid pointer-events-none"></div>

        <!-- Hero Text -->
        <div class="z-10 flex flex-col items-center text-white rounded-lg p-4 px-8">
            <h1 class="font-martian-mono text-[9rem] leading-none tracking-tight">LOGIN</h1>
        </div>
    </div>
</template>

<style>
.bg-grid {
    background-image: 
        linear-gradient(rgb(130, 142, 130, 0.66) 1px, transparent 1px),
        linear-gradient(90deg, rgb(130, 142, 130, 0.66) 1px, transparent 1px);
    background-size: 4rem 4rem; /* Matches text size */
    background-position: center;
    opacity: 0.25;
}
</style>