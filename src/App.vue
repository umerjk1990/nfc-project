<template>
  <div id="app">
    <logIn></logIn>
  </div>
</template>

<script>
import logIn from './components/logIn.vue'

export default {
  name: 'App',
  components: {
    logIn
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
  /* margin-top: 60px; */
}
</style>
