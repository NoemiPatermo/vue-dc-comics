<template>
  <div id="app">
    <Header /> 
    <Main :comics="comics"/> <!--prendi il jsons dalla funzione (comics in comics) e passalo al main-->
    <Merchandise />
    <Footer />
  
    
  
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Merchandise from './components/Merchandise.vue';
import Footer from './components/Footer.vue';
import comicsJson from './jsons/dc-comics.json'; //stai importando il jsons



export default {
  name: 'App',
  components: {
    Header,
    Main,
    Merchandise, 
    Footer
    
  },
  data: function() { //creiamo un function che ci ritorna il jsons perché non è component!
    return {
      comics: comicsJson,
      
    };
  },
}

</script>

<style lang="scss">
//importa scss generico
@import "./style/app.scss"

</style>
