<template>
  <div id="app">
    <router-link to="/js-pages">js01三种创建对象的方式</router-link>
    <router-link to="/js-pages">js02原型链</router-link>
    <router-view/>
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
  /* text-align: center; */
  color: #2c3e50;
}
#app a {
  display: block;
}
</style>
