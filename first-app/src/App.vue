<template>
  <div id="app">
    <Title/>
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Heroimage/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Title from './components/My-title.vue'
import Heroimage from './components/Hero-image.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Title,
    Heroimage
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
