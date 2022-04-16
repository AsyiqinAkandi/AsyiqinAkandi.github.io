<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>

  <!-- <HelloWorld msg="Hello Vue 3 + Vite" /> -->

  <div id="app" class="shadow-md rounded-md w-9/12 h-4/6 place-content-center">
    <img src="./assets/pfp.jpg" alt="Profile Picture" class="shadow-md rounded-full w-20 h-20">
    <br><h3 class="text-2xl underline">Khairunnisa' Asyiqin binti Akandi</h3>
    <div id="info">
      <p>D.O.B: 14/01/2000</p><br>
      <p>School: School of Information and Technology</p><br>
      <p>Institution: Politeknik Brunei</p><br>
      <p>Course: Diploma in Web Development</p>
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
