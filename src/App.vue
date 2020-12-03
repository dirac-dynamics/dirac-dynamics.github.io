<template>
  <div id="app">
    <ParticlesBackground/>
    <div id="content">
      <img id="logo" src='@/assets/logo_long_filled.png'/>
      <h2>Making Mobility More Efficient.</h2>
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
#content {
  position: relative;
  top: 30%;
  height: 0;
  display: inline-block;
}
#logo {
  width: 80%;
  -webkit-filter: invert(1);
  filter: invert(1);
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
