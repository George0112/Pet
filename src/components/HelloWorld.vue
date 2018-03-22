<template>
  <div class='HelloWorld'>
    <Navbar/>
  </div>
</template>

<script>
import Navbar from './Navbar.vue'

export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components: {
    Navbar
  }
}
</script>
