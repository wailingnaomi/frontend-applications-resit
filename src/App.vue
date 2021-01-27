<template>
  <div id="app">
    <Header />
    <Main /> 
    <Footer />
  </div>
</template>

<script>
import Header from './components/layout/Header';
import Main from './components/Main';
import Footer from './components/layout/Footer';

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@500;600&display=swap');

  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

  body{
    font-family: 'Montserrat', sans-serif;
    background-color: #f4f4f4;
    width: 50%;
    margin: 2em auto;
  
  }

  a{
    color: #000;
    text-decoration: none;
  }

  a:hover{
    color: #CCCCCC;
  }

  img{
      width: 100%;
  }
</style>
