<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <h2>Selamat Datang</h2>
    <Logos/>
  </div>
</template>

<script>
import Logos from './components/Logos.vue'

export default {
  name: 'App',
  components: {
    Logos
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
