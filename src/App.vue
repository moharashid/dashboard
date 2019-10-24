<template>
  <body>
    <Nav/>
  <Home/>
  </body>
</template>

<script>
import Nav from './components/Nav.vue'
import Home from './components/Home.vue'
export default {
  name: 'app',
  components: {
    Nav, Home
  }
}
</script>

<style>

</style>
