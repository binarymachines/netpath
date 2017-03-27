<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <!-- <hello></hello> -->
    <h3>Hello from HELL</h3>
    <testcomp/>
  </div>
</template>

<script>
import Hello from './components/Hello'
import Testcomp from './components/Testcomp'

export default {
  name: 'app',
  components: {
    Hello,
    Testcomp
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
