<!-- eslint-disable vue/no-unused-components -->
<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HomePage msg="Welcome again"/>
</template>

<script>
import HomePage from './components/HomePage.vue'
import NavBar from './components/NavBar.vue'
import PageFooter from './components/PageFooter.vue'

export default {
  name: 'App',
  components: {
    HomePage,
    NavBar,
    PageFooter
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
