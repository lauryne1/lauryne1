<template>
  <div>
    <NavBar class="fixed top-5 w-full z-10"></NavBar>
  </div>
  <div>
    <Home></Home>
  </div>

  <div>
    <Projects></Projects>
  </div>
  <div>
    <Skills></Skills>
  </div>
  <div>
    <Contact></Contact>
  </div>
</template>

<script setup lang="ts">
import NavBar from './components/NavBar.vue';
import Home from './components/Home.vue';
import Projects from './components/Projects.vue'
import Skills from './components/Skills.vue';
import Contact from './components/Contact.vue'

</script>

<style scoped></style>