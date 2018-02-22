<template>
  <div id="app">
    <vnav></vnav>
    <agora></agora>
    <vfooter></vfooter>
  </div>
</template>

<script>
import nav from './components/Web/Navigation'
import agora from './components/Web/Agora'
import footer from './components/Web/Footer'

export default {
  components: {
    vnav: nav,
    agora: agora,
    vfooter: footer
  },
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
