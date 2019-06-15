<template>
  <div id="app">
    <CobaHeader/>
    <CobaBody />
  </div>
</template>

<script>
import CobaHeader from './components/CobaHeader.vue'
import CobaBody from './components/CobaBody.vue'

export default {
  name: 'app',
  components: {
    CobaHeader,
    CobaBody
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
  margin-top: 60px;
}
</style>
