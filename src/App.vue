<template>
  <div id="app">
    <topology-map msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import TopologyMap from './components/TopologyMap.vue'

export default {
  name: 'App',
  components: {
    TopologyMap
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
