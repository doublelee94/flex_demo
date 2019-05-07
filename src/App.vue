<template>
  <div id="app">
    <flexDemo></flexDemo>
  </div>
</template>

<script>

import flexDemo from './components/flexDemo'


export default {
  name: 'app',
  components: {
    flexDemo
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
  }
  body {
    margin: 0;
  }
</style>
