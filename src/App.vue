<template>
  <!--<img alt="Vue logo" src="./assets/logo.png">-->
  <!--<HelloWorld msg="Welcome to Your Vue.js App"/>-->
  <Home />

</template>

<script>

//CSS
require('./css/style.css');

// Importing Components
//import HelloWorld from './components/HelloWorld.vue'

// Components
//import Menu from './components/Menu.vue'

// Views
import Home from './views/Home.vue'

export default {
  name: 'App',
  components: {
    Home,
    //HelloWorld
  }
}
</script>

<style>
/*
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
*/
</style>
