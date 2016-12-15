<template>
  <div id="app">
    <Navbar></Navbar>
    <Banner3></Banner3>
    <Showplay></Showplay>
    <footers></footers>
  </div>
</template>

<script>
import Mains from './components/Mains'
import Showplay from './components/Showplay'
import Navbar from './components/Navbar'
import Banner from './components/Banner'
import Footers from './components/Footers'
import Banner2 from './components/Banner2'
import Menu from './components/Menu'
import Banner3 from './components/Banner3'

export default {
  name: 'app',
  components: {
    Mains,
    Showplay,
    Navbar,
    Banner,
    Footers,
    Banner2,
    Banner3,
    Menu
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
