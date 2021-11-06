<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <ul class="icons">
    <li><icon-check /></li>
    <li><icon-check :stroke=8 /></li>
    <li><icon-check :size=128 :stroke=0.2 /></li>
    <li><icon-check :size=64 :stroke=6 color="#41b883" /></li>
  </ul>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
ul.icons {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
  align-items: center;
  justify-content: center;
}
ul.icons li {
  background: #e5e5e5;
  width: 150px;
  height: 150px;
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 2px;
}
</style>
