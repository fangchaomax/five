<template>
  <div id="app">
    <top></top>
  </div>
</template>

<script>
import top from './components/kj'

export default {
  name: 'app',
  components: {
    kj
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
