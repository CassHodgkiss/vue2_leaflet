<template>
  <div id="app">
    <MainIndex />
  </div>
</template>

<script>
import MainIndex from './components/Index.vue'

export default {
  name: 'App',
  components: {
    MainIndex
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
