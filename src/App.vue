<template>
<div id="app">
  <Navbar  />
  <Header />
  <ScrollMenu />
  <TopProducts />
</div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Header from './components/Header.vue'
import ScrollMenu from './components/ScrollMenu.vue'
import TopProducts from './components/TopProducts.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Header,
    ScrollMenu,
    TopProducts
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
