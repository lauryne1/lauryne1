<template>
  <div class="mt-2 min-h-screen">
    <div id="particles-js" class="absolute top-0 left-0 w-full h-full z-0"></div>
    <div class="text-white text-center py-44">
      <div class="mx-auto mb-8 w-24 h-24 border-2 border-white rounded-full overflow-hidden">
        <img src="/profil.jpeg" class="w-full h-full object-cover rounded-full" />
      </div>

      <h2 class="text-3xl mb-3">Hello, I'm Lauryne.I'm a front end developper.</h2>
      <h2 class="text-3xl mb-3">I spend my day working on web apps</h2>
      <h2 class="text-3xl mb-3">with TypeScript,React.js,Vue.js PHP.</h2>
      <h2 class="text-3xl mb-3"></h2>
      <div class="flex justify-center space-x-4 mt-20">
        <!-- <div class="flex  space-x-3">
                    <a href="https://github.com/yourusername" target="_blank"
                        class="px-10 py-3 border border-transparent text-base font-medium rounded-full text-blue-950 bg-white ">GitHub
                        <githublogo  />

                    </a>
                </div> -->
        <div class="flex items-center space-x-2">
          <a
            href="https://github.com/yourusername"
            target="_blank"
            class="flex items-center px-5 py-3 border border-transparent text-base font-medium rounded-full text-blue-950 bg-white"
          >
            <span>GitHub</span>
            <img src="/githubIcon.png" class="h-6 w-7 ml-2" />
          </a>
        </div>
        <div class="flex items-center space-x-3">
          <a
            href="https://linkedin.com/in/yourusername"
            target="_blank"
            class="px-5 py-3 flex items-center bg-black border border-gray-300 text-base font-medium rounded-full text-gray-300"
          >
            <span>LinkedIn</span>
            <img src="/linkIcon.png" class="h-6 w-6 ml-2" />
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import { onMounted } from 'vue'
declare const particlesJS: any

onMounted(() => {
  particlesJS('particles-js', {
    particles: {
      number: { value: 80, density: { enable: true, value_area: 1000 } },
      size: { value: 3 }
    }
  })
})
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
