<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <TitleComp></TitleComp>
    <HeroJumbo></HeroJumbo>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TitleComp from './components/TitleComp.vue'
import HeroJumbo from './components/HeroJumbo.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    TitleComp,
    HeroJumbo
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
