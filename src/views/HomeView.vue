<template>
  <div class="home">
    <BannerComp/>
    <IntroComp/>
    <ProcesoComp/>
    <ProductosComp/>
  
  </div>
</template>

<script>

  import BannerComp from '@/components/home/BannerComp.vue'
  import IntroComp from '@/components/home/IntroComp.vue'
  import ProcesoComp from '@/components/home/ProcesoComp.vue'
  import ProductosComp from '@/components/home/ProductosComp.vue'


  export default {

    name: 'HomeView',

    components: {
     BannerComp, IntroComp, ProductosComp, ProcesoComp, 
    }

  }

</script>
