<template>
    <div id="boton_flotante" 
        >
        <v-btn
            class="boton"
            href="#section_banner"
        >   
            <a class="enlace_boton"> <v-icon>mdi-arrow-up</v-icon></a>
           
        </v-btn>  

    </div>
</template>

<style lang="scss">
    #boton_flotante{
        .boton{
            position: fixed;
            top: 95%;
            right: 1%;
        }
    }
</style>

<script>

export default {
    
    methods: {
    },
  }

</script>