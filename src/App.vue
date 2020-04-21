<template>
  <div id="app">
    <filePreview />
  </div>
</template>

<script>
import filePreview from './components/filePreview.vue'

export default {
  name: 'App',
  components: {
    filePreview
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
