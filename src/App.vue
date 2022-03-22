<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <test-one></test-one>
  </div>
</template>

<script>
import TestOne from "./components/Test-one.vue";
export default {
  name: 'App',
  components: {
TestOne
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
