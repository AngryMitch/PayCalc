<template>
  <NavMain/>
</template>

<script>
import NavMain from './components/Layout/NavBar.vue'

export default {
  name: 'App',
  components: {
    NavMain
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
