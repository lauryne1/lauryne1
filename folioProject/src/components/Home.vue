<template>
    <div class="mt-20 min-h-screen">
        <div id="particles-js" class="absolute top-0 left-0 w-full h-full z-0">
        </div>
        <div class="relative z-10 text-white text-center py-44">
            <h2 class="text-3xl mb-3">Hello, I'm Lauryne.I'm a front end developper.</h2>
            <h2 class="text-3xl mb-3"> I spend my day working on web apps</h2>
            <h2 class="text-3xl mb-3"> with TypeScript,React.js,Vue.js PHP.</h2>
            <h2 class="text-3xl mb-3">
            </h2>
            <div class="flex justify-center space-x-4  mt-7">
                <div class="flex flex-col space-x-3">
                    <a href="https://github.com/yourusername" target="_blank"
                        class="px-10 py-3 border border-transparent text-base font-medium rounded-full text-blue-950 bg-white ">GitHub

                    </a>
                    <githublogo class="bg-red-500 " />
                </div>

                <a href="https://linkedin.com/in/yourusername" target="_blank"
                    class="px-10 py-3 border border-transparent text-base font-medium rounded-full text-blue-950 bg-white ">LinkedIn</a>
            </div>
        </div>
    </div>
</template>

<script setup lang="ts">
import { onMounted } from 'vue';
import type githublogo from './icons/githublogo.vue';
declare const particlesJS: any;


onMounted(() => {
    particlesJS('particles-js', {
        particles: {
            number: { value: 80, density: { enable: true, value_area: 1000 } },
            size: { value: 3 }
        },
    });
});
</script>

<style scoped>
#particles-js {
    position: absolute;
    width: 100%;
    height: 100%;
    background-color: #27103d;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: 50% 50%;
    z-index: -1;
}
</style>