<template>
    <h1 class=" flex items-center justify-center mt-24">Skills</h1>
    <div class="flex items-center justify-center mt-7">Programming languages, frameworks and other tools I work with.</div>
    <div class="p-8 flex justify-center items-center mt-4">
        <div class="grid grid-cols-4 gap-8">
            <div class="flex flex-col items-center justify-center bg-white rounded-lg shadow-md p-12">
                <vueIcon />
                <p class="text-sm">Vue.js</p>
            </div>
            <div class="flex flex-col items-center justify-center bg-white rounded-lg shadow-md p-12 ">
                <tailwindIcon />
                <p class="text-sm">Tailwind</p>
            </div>
            <div class="flex flex-col items-center justify-center bg-white rounded-lg shadow-md p-12 ">
                <gitIcon />
                <p class="text-sm">Git</p>
            </div>
            <div class="flex flex-col items-center justify-center bg-white rounded-lg shadow-md p-12 ">
                <nodeIcon />
                <p class="text-sm">Node.js</p>
            </div>
            <!-- Deuxième ligne de la grille avec 4 icônes -->
            <div class="flex flex-col items-center justify-center bg-white rounded-lg shadow-md p-12 ">
                <htmlIcon />
                <p class="text-sm">HTML</p>
            </div>
            <div class="flex flex-col items-center justify-center bg-white rounded-lg shadow-md p-12 ">
                <mysqlIcon />
                <p class="text-sm">MySQL</p>
            </div>
            <div class="flex flex-col items-center justify-center bg-white rounded-lg shadow-md p-12 ">
                <reactIcon />
                <p class="text-sm">React</p>
            </div>
            <div class="flex flex-col items-center justify-center bg-white rounded-lg shadow-md first-letter:p-12 ">
                <figmaIcon />
                <p class="text-sm">Figma</p>
            </div>
        </div>
    </div>
</template>
  
<script setup lang="ts">
import vueIcon from './icons/vueIcon.vue';
import tailwindIcon from './icons/tailwindIcon.vue';
import gitIcon from './icons/gitIcon.vue';
import nodeIcon from './icons/nodeIcon.vue';
import htmlIcon from './icons/htmlIcon.vue';
import mysqlIcon from './icons/mysqlIcon.vue';
import reactIcon from './icons/reactIcon.vue';
import figmaIcon from './icons/figmaIcon.vue';
</script>
  
  