<template>
<div id="app">
  <img alt="Vue logo" src="./assets/logo.png">
  <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
  
  <!-- <HomePage data="Vijay is here"/> -->
  <HomePage data="Vijay is here" msg="hi from vijay0"/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

import HomePage from './components/HomePage.vue'
export default {
  name: 'App',
  components: {
    // HelloWorld,
    HomePage
}
}
</script>

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
