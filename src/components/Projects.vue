<template>
    <div class="flex flex-col">
        <div class="text-blue-950  flex justify-center text-xl items-center font-bold"> My Projects</div>

        <div class="p-8 flex justify-center items-center">
            <div class="p-4 border rounded-xl bg-slate-50 shadow-lg flex flex-col md:flex-row items-start">
                <div class="max-w-full flex flex-col space-x-10">
                    <div class="font-bold mb-4">ToDoApp</div>
                    <div class="flex space-y-2 items-center justify-start mb-4 ">
                        <p>Made with:</p>
                        <div class="flex">
                            <img src="vueLogo.png"
                                class="icon transition-transform transform hover:scale-125  w-10 h-9" />
                            <img src="/tailwindIcon.png" class=" w-11 h-11 mr-2" />
                        </div>
                    </div>
                    <p class="max-w-xs ">
                        Ma ToDoApp is a task management application designed to help professionals stay organized and
                        productive. With features such as creating, editing and deleting tasks, as well as the ability
                        to
                        categorize tasks and set reminders, our app offers a complete solution for managing daily to-do
                        lists and complex projects. Developed with Vue.js and styled with Tailwind CSS, our application
                        combines power and ease of use to deliver an exceptional user experience.
                    </p>
                    <div class="flex items-center space-x-2">
                        <a href="https://github.com/lauryne1/todo-app" target="_blank"
                            class="flex items-center px-3 py-2 mt-6  border border-black text-base font-medium rounded-full text-blue-950 bg-white">
                            <img src="/githubIcon.png" class=" w-6 h-6 mr-2" />


                            <span>GitHub</span>
                        </a>
                    </div>
                </div>
                <img class="flex mx-8 mt-6 transition-transform transform-gpu hover:-rotate-6" src="TodoApp.png"
                    alt="Image de ToDoApp" />
            </div>
        </div>

        <div class="p-8 flex justify-center items-center">
            <div class="p-4 border rounded-xl bg-slate-50 shadow-lg flex flex-col md:flex-row items-start">
                <div class="max-w-full flex flex-col space-x-10">
                    <div class="font-bold mb-4">Vanilla</div>
                    <div class="flex space-y-2 items-center justify-start mb-4 ">
                        <p>Made with:</p>
                        <div class="flex">
                            <img src="vueLogo.png"
                                class="icon transition-transform transform hover:scale-125  w-10 h-10" />

                            <img src="/cssIcon.png" class=" w-11 h-11 " />


                        </div>
                    </div>
                    <p class="max-w-xs ">
                        Ma Vanilla project is a Develop an image gallery where users can browse different images and
                        view details about each image.
                    </p>
                    <div class="flex items-center space-x-2">
                        <a href="https://github.com/lauryne1/todo-app" target="_blank"
                            class="flex items-center px-3 py-2 mt-6  border border-black text-base font-medium rounded-full text-blue-950 bg-white">
                            <img src="/githubIcon.png" class=" h-5 w-6 mx-1" />

                            <span>GitHub</span>
                        </a>
                    </div>
                </div>
                <img class="flex mx-8 mt-6 transition-transform transform-gpu hover:-rotate-6" src="vanilla.png"
                    alt="Image de ToDoApp" />
            </div>
        </div>
    </div>



</template>

<script setup lang="ts">
import TailwindIcon from './icons/tailwindIcon.vue';
import CssIcon from './icons/CssIcon.vue';
import VueIcon from './icons/vueIcon.vue';





</script>

<!-- <style>
img:hover {
    transform: rotateX(15deg);
}
</style> -->

<style>
/* img:hover {
    transform: rotate(2deg) translate(5px, 3px);
    Réglez les valeurs selon vos besoins
} */
</style>
