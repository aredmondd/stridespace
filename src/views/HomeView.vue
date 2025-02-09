<script setup>
import Hero from '@/components/Hero.vue';
import BreathingText from '@/components/BreathingText.vue';
import { RouterLink } from 'vue-router';
</script>

<template>
    <main class="flex flex-col flex-1">
        <div class="flex justify-center items-center mt-24">
            <div class="flex flex-col">

                <div class="flex items-center text-purple rounded-lg p-4 px-8">
                    <h1 class="font-martian-mono text-9xl">STRIDESPACE</h1>
                    <!-- <span class="text-purple text-8xl mt-[-10px]">*</span> -->
                </div>


                <div class="flex justify-around font-martian-mono text-3xl p-2 text-white opacity-50">
                    <p>find</p>
                    <p>new</p>
                    <p>ways</p>
                    <p>to</p>
                    <p>see</p>
                    <p>your</p>
                    <p>runs</p>
                </div>

            </div>
        </div>

        <div class="flex justify-around mt-24">
            <div class="rounded-lg py-6 px-12">
                <div class="font-martian-mono text-center">visualize running data</div>
                <img src="../assets/abstract_run_art.png" alt="" width="340" class="mt-4">
            </div>
            <div class="rounded-lg py-6 px-12">
                <div class="font-martian-mono text-center">generate art based on your run</div>
                <img src="../assets/abstract_run_art.png" alt="" width="340" class="mt-4">
            </div>    
            <div class="rounded-lg py-6 px-12">
                <div class="font-martian-mono text-center">find new communities</div>
                <img src="../assets/abstract_run_art.png" alt="" width="340" class="mt-4">
            </div>        
        </div>

        <!-- <div class="flex mt-24">
            <div class="border-2 border-purple rounded-lg">
                <div class="bg-white rounded-full p-8 opacity-50"></div>
            </div>
        </div> -->

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
