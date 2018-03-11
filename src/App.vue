<template>
  <div id="app">
    <header style="position: relative;">
      <router-link to="/" exact><img src="./assets/logo.png" style="height: 5vh; width: 5vh;"></router-link>
      <router-link to="/hello">Start</router-link>
    </header>
    <router-view></router-view>
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
  margin-top: 40px;
}
.router-link-active {
  color: turquoise;
}
</style>
