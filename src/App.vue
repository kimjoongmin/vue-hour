<template>
  <div id="app">
    <div id="wrap">
      <Header />
      <div id="container">
        <router-view></router-view>
      </div>
      <Footer />
    </div>
  </div>
</template>

<script>
import Header from './components/layout/Header.vue'
import Footer from './components/layout/Footer.vue'
import '@/assets/css/injeinc/base.css'
import '@/assets/css/base.css'
//import '@/assets/css/content.css'

export default {
  name: 'App',
  components: {
    Header,
    Footer
  }
}
</script>

<style>
  html,body{text-align:center;}
</style>
