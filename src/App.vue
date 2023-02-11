<template>
  <div id="app">
    <v-app>
      <MenuComp/>
      <router-view/>
      <FooterComp/>
    </v-app>
  </div>
</template>

<script>

  import MenuComp from '@/components/MenuComp.vue'
  import FooterComp from '@/components/FooterComp.vue'


  export default {

    name: 'HomeView',

    components: {
      MenuComp,  FooterComp
    }

  }

</script>

<style lang="scss">

  :root{
    --blanco: #ffffff;
    --negro: #000000;
    --azul: #0F70B7;
    --azul-oscuro: #267EBE;
    --verde: #25D366;
    --turquesa: #0B94C9;
  }

  html {
    scroll-behavior: smooth;
    scroll-margin-top: 5rem;
  }

  a{
    text-decoration: none;
  }

  ul {
      padding: 0;
      margin: 0;
  }

  li{
    list-style: none;
  }

  #app {

    /*Generales*/

    .titulo{
      font-family: "good-times", sans-serif;
      font-weight: 700;
      font-style: normal;
      color: var(--azul-oscuro);
    }

    .titulo_card{
      font-family: "good-times", sans-serif;
      font-weight: 400;
      font-style: normal;
      color: var(--azul-oscuro);
    }

    .texto{
      font-family: "poppins", sans-serif;
      font-weight: 400;
      font-style: normal;
      color: var(--negro);
    }

    .boton{
      background: var(--azul-oscuro);
    }

    .boton_whats{
      background: var(--verde);
    }

    .enlace_boton{
      color: var(--blanco);
    }

    .enlace{
      font-family: "good-times", sans-serif;
      font-weight: 400;
      font-style: normal;
    }

    .reveal {
      position: relative;
      opacity: 0;    
    }
  
   .reveal.active {
      opacity: 1;
    } 

    .active.fade-left{
      -webkit-animation: fade-left 1s ease-in;
              animation: fade-left 1s ease-in;
  }
  
  
  @-webkit-keyframes fade-left {
      0% {
        -webkit-transform: translateX(-100px);
                transform: translateX(-100px);
        opacity: 0;
      }
      100% {
        -webkit-transform: translateX(0);
                transform: translateX(0);
        opacity: 1;
      }
    }
  
  
  @keyframes fade-left {
      0% {
        -webkit-transform: translateX(-100px);
                transform: translateX(-100px);
        opacity: 0;
      }
      100% {
        -webkit-transform: translateX(0);
                transform: translateX(0);
        opacity: 1;
      }
    }

    .active.fade-right{
      -webkit-animation: fade-right 1.5s ease-in;
              animation: fade-right 1.5s ease-in;
  }
  
  
  @-webkit-keyframes fade-right {
      0% {
        -webkit-transform: translateX(100px);
                transform: translateX(100px);
        opacity: 0;
      }
      100% {
        -webkit-transform: translateX(0);
                transform: translateX(0);
        opacity: 1;
      }
    }
  
  
  @keyframes fade-right {
      0% {
        -webkit-transform: translateX(100px);
                transform: translateX(100px);
        opacity: 0;
      }
      100% {
        -webkit-transform: translateX(0);
                transform: translateX(0);
        opacity: 1;
      }
    }
  }
</style>
