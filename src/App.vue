<template>
  <div id="app">
    <Navbar></Navbar>
    <MainHome></MainHome>
    <Footer></Footer>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'
import MainHome from './components/MainHome.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Footer,
    MainHome
  }
}
</script>

<style>
#app {
  font-family: 'Avenir-Next', 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #333;
}
</style>
