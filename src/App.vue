<template>
  <div id="app">
    <Navbar></Navbar>
    <mains></mains>
  </div>
</template>

<script>
import Mains from './components/Mains'
import Showplay from './components/Showplay'
import Navbar from './components/Navbar'

export default {
  name: 'app',
  components: {
    Mains,
    Showplay,
    Navbar
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
}
</style>
