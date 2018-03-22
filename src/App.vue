<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar'
import HelloWorld from '@/components/HelloWorld.vue'
export default {
  name: 'App',
  components: {
    Navbar,
    HelloWorld
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
}
</style>

Vue.component('b-modal', bModal);
Vue.directive('b-modal', bModalDirective);
