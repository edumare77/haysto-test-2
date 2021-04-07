<template>
  <div class="content antialiased">
    <Header></Header>
  
    <Welcome></Welcome>
    <Footer></Footer>
  </div>
</template>

<script>
import Welcome from './components/Welcome.vue'
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Welcome,
    Header,
    Footer
  }
}
</script>

<style>

</style>
