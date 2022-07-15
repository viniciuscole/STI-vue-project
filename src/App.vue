<template>
  <Navbar/>
  <MainContent/>
  <Footer/>
</template>

<script>

import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'
import MainContent from './components/MainContent.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Footer,
    MainContent
  }
}
</script>

<style>
  html{
    background-color: #f2e5f9;
  }
</style>
