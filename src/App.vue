<template>
  <div id="app">
    <ParticlesBackground/>
    <div id="text">
      <h1>|Dirac Dynamics></h1>
      <h2>Enjoy the Quantum Revolution.</h2>
    </div>
  </div>
</template>

<script>
import ParticlesBackground from './components/ParticlesBackground.vue'

export default {
  name: 'App',
  components: {
    ParticlesBackground
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
  position: absolute;
  width: 100%;
  height: 100%;
}
#text {
  position: relative;
  top: 30%;
  height: 0;
}
h1 {
  font-size: 500%;
}

h2 {
  font-size: 200%;
}

html, body {
  margin: 0px !important;
  padding: 0px !important;
  background-color: black;
}
</style>
