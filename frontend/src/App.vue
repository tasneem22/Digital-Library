<template>
  <div id="app">
      <v-wrapper></v-wrapper>
  </div>
</template>

<script>import vWrapper from './components/v-wrapper';
export default {
  name: 'App',
  components: {
    vWrapper
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
  margin-top: 1vh;
    height: 100%;
    width: 100%;
}
</style>
