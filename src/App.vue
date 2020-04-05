<template>
  <div id="app">
   <SideMenu msg="Welcome to Your Vue.js App"/>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import SideMenu from './components/sidemenu.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    SideMenu
  }
}
</script>

<style scoped lang="scss">
*{
  padding:0px;
  margin:0px;
  
}
body{
  margin:0px;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height:100%;
}
</style>
