<template>
  <div>
    <Navbar />
    <Jumbotron />
    <TagLine />
    <Album />
    <Footer />  
  </div>
  
</template>

<script>
import Navbar from './components/Navbar.vue'
import Jumbotron from './components/Jumbotron.vue'
import TagLine from './components/TagLine.vue'
import Album from './components/Album.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Jumbotron,
    TagLine,
    Album,
    Footer
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
}
</style>
