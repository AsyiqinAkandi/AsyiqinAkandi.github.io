<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>

  <!-- <HelloWorld msg="Hello Vue 3 + Vite" /> -->

  <div id="app" class="shadow-md rounded-md grid grid-cols-1 gap-4 m-auto w-4/5 bg-gray-100 p-8">
    <img src="./assets/pfp.png" alt="Profile Picture" class="shadow-md rounded-full w-20 h-20 place-content-center m-auto">
    <h3 class="text-2xl underline">Khairunnisa' Asyiqin binti Akandi</h3>
    <div id="info">
      <p>School: School of Information and Technology</p>
      <p>Institution: Politeknik Brunei</p>
      <p>Course: Diploma in Web Development</p>
      <p>Contact me @ 20FTT1461</p>
    </div>
  </div>

</template>

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
