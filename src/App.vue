<template>
  <div id="app">
    <Welcome/>
    <Calculator/>
  </div>
</template>

<script>
import Calculator from './components/Calculator.vue'
import Welcome from './components/Welcome.vue'

export default {
  name: 'app',
  components: {
    Calculator,
    Welcome
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
  background-color: aqua;
  height: 100vh
}
</style>
