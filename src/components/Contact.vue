<template>
    <div class="flex flex-col items-center mt-14">
        <div class="text-2xl font-bold mb-6">Contact Me</div>
        <div class="mb-6">Please contact me directly at <a href="mailto:laurynejosiasdady@gmail.com"
                class="underline">laurynejosiasdady@gmail.com</a> or use this form.</div>

        <form action="mailto:laurynejosiasdady@gmail.com" method="post" enctype="text/plain" class="flex flex-col">
            <input type="email" name="email" placeholder="Your email"
                class="w-[590px] h-11 rounded-md outline-none border-gray-300 border mt-4 px-4" required>

            <textarea name="message" placeholder="Your Message"
                class="w-[590px] h-40 rounded-md border-gray-300 border mt-4 outline-none px-4 py-2"
                required></textarea>

            <button type="submit"
                class="bg-black text-white w-32 font-bold py-3 px-4 rounded-3xl mt-4 flex items-center">
                <span class="flex items-center justify-center">Submit</span>
                <SubmitIcon class="ml-2 h-5 w-7 " />
            </button>
        </form>
    </div>
</template>

<script setup lang="ts">
import SubmitIcon from './icons/SubmitIcon.vue'
</script>

<style scoped></style>
