<template>
    <section id="rfid">
        <v-container>
          <DescriptionComp/>
          <VentajasComp/>
          <CuentanosComp/>
        </v-container>     
    </section>
</template>

<script>

import DescriptionComp from '@/components/rfid/DescriptionComp.vue'
import VentajasComp from '@/components/rfid/VentajasComp.vue'
import CuentanosComp from '@/components/rfid/CuentanosComp.vue'

  export default {

    name: 'HomeView',

    components: {
      DescriptionComp, VentajasComp,  CuentanosComp
    }

  }

</script>

    
<style lang="scss">

</style>
