<template>
  <div id="app">
    <department/>
 
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Department from './components/Department.vue'

export default {
  name: 'App',
  components: {
  //  HelloWorld
  Department
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
