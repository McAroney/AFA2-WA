<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <weatherApp msg="This is Wreather App with Vue.js"/>
</template>

<script>
import weatherApp from './components/weatherApp.vue'

export default {
  name: 'App',
  components: {
    weatherApp
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
