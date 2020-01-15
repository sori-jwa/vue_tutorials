<template>
  <div id="app">
    <img src="./assets/logo.png">
    <!-- <img src="./" alt=""> -->
    <h1>ToDo Managemant.</h1> <!-- add-->
    <hr />
    <router-view></router-view> <!-- replace-->
  </div>
</template>

<script>
export default {
  name: 'App'
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
