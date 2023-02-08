<template>
    <section id="section_intro">
        <v-container class="">
            <v-row 
                align="end"
                justify="center"
            >
                <v-col  
                    align="center"
                    justify="center"
                    cols="10"
                    sm="5"
                    md="3"
                >
                    <a href="#etiquetas_impresas">
                        <div class="card mb-5">
                            <h1 class="titulo_card text-uppercase mb-3">Etiqueta Impresa</h1>
                            
                                <v-img 
                                    class="img_card"
                                    src="../../assets/images/cards/etiquetas.jpg"                        
                                >
                                </v-img>
                        </div>   
                    </a>
                </v-col>
                
                <v-col
                    align="center"
                    justify="center"
                    cols="10"
                    sm="5"
                    md="3"
                >   
                    <a href="#etiquetas_especiales">
                        <div class="card mb-5">
                            <h1 class="titulo_card text-uppercase mb-3">Etiqueta Especial</h1>
            
                        <v-img class="img_card"
                                    src="../../assets/images/cards/especiales.jpg"
                                >
                                </v-img>
                        </div>
                    </a>
                </v-col>
                
                <v-col
                    align="center"
                    justify="center"
                    cols="10"
                    sm="5"
                    md="3"
                >
                    <a href="#hardware_software">
                        <div class="card mb-5">
                            <h1 class="titulo_card text-uppercase mb-3">Hardware / Software</h1>
            
                            <v-img class="img_card"
                                src="../../assets/images/cards/hardware.jpg"
                                >
                                </v-img>
                        </div>
                    </a>
                </v-col>
                
                <v-col
                    align="center"
                    justify="center"
                    cols="10"
                    sm="5"
                    md="3"
                >
                    <a href="#proyectos_integrales">
                        <div class="card mb-5">
                            <h1 class="titulo_card text-uppercase mb-3">Integración de proyectos</h1>
            
                            
                                <v-img class="img_card"
                                    src="../../assets/images/cards/proyectos.jpg"
                                >
                                </v-img>
                        </div> 
                    </a>     
                </v-col>
            </v-row>           
        </v-container>
    </section>
</template>

<style lang="scss">

    #section_intro{
        .card{
            width: 100%;

            .img_card{
                    width: 100%;
                    border-radius: 14px;
                }
            }
        
    }

</style>