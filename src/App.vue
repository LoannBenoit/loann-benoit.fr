<template>
  <div id="app">
    <NavBar msg="Welcome to Your Vue.js App"/>
    <Home/>
  </div>
</template>

<script>
import NavBar from '@/components/NavBar.component'
import Home from '@/components/Home.component'

export default {
  name: 'App',
  components: {
    NavBar,
    Home
  }
}
</script>

<style>
html, body {
  width: 100%;
  height: 100%;
}

div#app {
  margin: 0px;
}

#app {
  width: 100%;
  height: 100%;
  margin: 0px;
  background: black;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
