<template>
  <div id="app">
    <random-translate></random-translate>
  </div>
</template>

<script>
import RandomTranslate from './components/RandomTranslate.vue'

export default {
  name: 'App',
  components: {
    RandomTranslate
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
