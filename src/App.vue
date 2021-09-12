<template>
<div id="app">
  <Heading/>
  </div>
</template>

<script>
import Heading from './components/Heading.vue'

export default {
  name: 'App',
  components: {
    Heading
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
  margin-top: 30px;
}
</style>
