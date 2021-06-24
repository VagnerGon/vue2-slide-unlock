<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <SlideUnlock msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import SlideUnlock from './components/SlideUnlock.vue'

export default {
  name: 'App',
  components: {
    SlideUnlock
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
