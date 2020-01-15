<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <!-- <router-view/> -->
    <!-- <hello></hello> -->
    <switch-to-tabs></switch-to-tabs>

  </div>
</template>

<script>

// import hello from './components/hello'
import switchToTabs from './view/switch/switchToTabs'

export default {
  name: 'App',
  components:{
    switchToTabs
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
