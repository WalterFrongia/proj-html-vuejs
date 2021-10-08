<template>
  <div id="app">
    <Header/>
    <Main/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer,
  }
}
</script>

<style lang="scss">

@import "./style/variables.scss";
@import 'bootstrap/scss/bootstrap.scss';
@import "~@fortawesome/fontawesome-free/css/all.css";

body{
    font-family:'Open Sans', sans-serif;
    p,li,button{
        font-size:1.2rem;    
    }
    h1{
        font-size: 3.5rem;
        font-weight: 300;
    }
}

</style>
