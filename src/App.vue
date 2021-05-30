<template>
  <div>
    <Homepage />
    <Slideshow />
    <Footer />
  </div>
</template>

<script>
import Homepage from './components/Homepage'
import Slideshow from './components/Slideshow'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Homepage,
    Slideshow,
    Footer,
  }
}
</script>

<style>
#app {
  font-family: 'Josefin Sans', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

body{
    background-color: rgba(158, 76, 0, 0.692);
}
</style>
