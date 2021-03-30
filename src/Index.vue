<template>
  <div id="app">
    <Header />
    <About />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import About from './components/About.vue'

export default {
  name: 'Index',
  components: {
    Header,
    About
  }
}
</script>

<style>
#app {
  font-family: -apple-system, BlinkMacSystemFont, 
    "Segoe UI", "Roboto", "Oxygen", 
    "Ubuntu", "Cantarell", "Fira Sans", 
    "Droid Sans", "Helvetica Neue", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2a2135;
  background-color: #fbf4ff;
}
</style>