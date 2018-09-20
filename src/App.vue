<template>
  <div id="app">
    <img src="./assets/logo.png">
    <HelloWorld/>
    <Alert></Alert>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import Alert from "./components/Alert"
export default {
  name: 'App',
  components: {
    HelloWorld,
    Alert
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
