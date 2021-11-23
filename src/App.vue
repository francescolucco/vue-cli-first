<template>
  <div class="container">
    <Title />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Title,
    Main,
    Footer,
  }
}
</script>

<style>
  .container{
    width: 80%;
    background-color: black;
    text-align: center;
    margin: 0 auto;
    padding: 30px;
  }
</style>
