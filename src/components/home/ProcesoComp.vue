<template>
    <section id="section_proceso">
        <v-container>         
            <h1 class="titulo text-center mb-16">Expertos en el proceso</h1>
            <v-row 
            align="center"
            justify="center"
            >
                <v-col
                    cols="12"
                    sm="4"
                    lg="3"
                    class="mx-auto mb-5 mx-lg-3"
                    align="center"
                    justify="center"
                >   
                    <h2 class="titulo_lottie mb-5 mb-sm-10">Gestión y automatización de almacenes</h2>
                    <div class="cont_lottie">
                        <lottie-player class="lottie" src="https://lottie.host/76c67ad0-4189-486e-b681-fbefdca76ac7/rnCQU8aTiz.json" background="transparent" speed="1"  loop autoplay></lottie-player>
                    </div>                    
                </v-col>

                <v-col
                    cols="12"
                    sm="4"
                    lg="3"
                    class="mx-auto mb-5 mx-lg-3 col_central"
                    align="center"
                    justify="center"             
                >
                    <h2 class="titulo_lottie mb-5 mb-sm-10">Trazabilidad de
                        producto</h2>
                    <div class="cont_lottie">
                        <lottie-player class="lottie" src="https://lottie.host/b91169f8-51fa-4a15-8e5b-a8282c54dad2/g8YJw303Hs.json" background="transparent" speed="1"  loop autoplay></lottie-player>
                    </div> 
                </v-col>
                <v-col
                    cols="12"
                    sm="4"
                    lg="3"
                    class="mx-auto mb-5 mx-lg-3"
                    align="center"
                    justify="center"           
                >
                    <h2 class="titulo_lottie mb-5 mb-sm-10">Etiquetado de
                        producto</h2>
                    <div class="cont_lottie">
                        <lottie-player class="lottie" src="https://lottie.host/0c578734-e48a-4f9b-8fde-8d565664dafb/3UPRmstQ5x.json" background="transparent" speed="1"  loop autoplay></lottie-player>
                    </div> 
                </v-col>
            </v-row>   
        </v-container>
    </section>
</template>

<style lang="scss">
    #section_proceso{

        .col_central{
            .titulo_lottie {
                border-left: 5px solid var(--azul-oscuro);
                border-right: 5px solid var(--azul-oscuro);
            }
        }

        .cont_lottie{
            width: 80%;
            .lottie{
                width: 100%;
            }
        }

    }
</style>