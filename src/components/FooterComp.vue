<template>
    <footer id="footer">
        <v-container >
            <v-row class="justify-center align-center">            
                <v-col 
                    cols="6"
                    sm="3" 
                    md="3"
                    lg="2 "
                    class="mx-auto d-flex flex-column justify-center align-center"
                >
                    <div class="cont_imagen mx-auto">
                        <img src="../assets/images/internal/logo.png" alt="">
                    </div>
                </v-col>
                <v-col 
                    cols="12"
                    sm="6"  
                    md="8"
                    class="mx-auto "
                >                                            
                    <a class="enlace my-2 text-center text-sm-end d-inline-block" target="_blank" href="">Física 14 Industrial Querétaro,  Qro.</a>
                    <a class="enlace my-2 text-center text-sm-end d-inline-block" href="tel:+524426291735">(442) 629 17 35</a>  
                    <p class="texto my-2 text-center text-sm-end text-uppercase">Atia Corporativo Tecnológico | {{fecha}}</p>
                </v-col>
            </v-row>
        </v-container>
    </footer>
</template>

<script>
    export default {
        data(){
            return{
                fecha: '',
            }        
        },
        created(){
            var date = new Date();
            this.fecha = date.getFullYear();
        }

    }
</script>

<style lang="scss">

#footer{
    background: var(--turquesa);

    .cont_imagen{
        width: 100%;

        img{
            width: 100%;
        }
    }

    .enlace, 
    .texto{
        color: var(--blanco) !important;
        max-height: 1rem;
        width: 100%;
    }

    .enlace:hover{
        color: var(--negro) !important;
    }

}

</style>