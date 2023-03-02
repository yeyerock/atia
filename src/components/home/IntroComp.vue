<template>
    <section id="section_intro">
        <v-container class="">
            <v-row 
                class="cont_btn_inicio mb-10 justify-center justify-lg-end"

            >
                <v-btn 
                    class="boton_whats"
                    dark    
                    x-large
                >
                <a href="https://api.whatsapp.com/send?phone=5214441787150&text=Hola%20quisiera%20información%20sobre%20sus%20productos" class="enlace_boton" target="_blank">Cotizar proyecto <v-icon class="mx-2">mdi-whatsapp</v-icon></a>
                </v-btn>
            </v-row>
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
                    lg="2"
                >
                    <a href="#etiquetas_impresas">
                        <div class="card mb-5">
                            <h1 class="titulo_card text-uppercase mb-3">Etiqueta Impresa</h1>
                            
                            <div class="img_card">
                                <v-img class="img"
                                    src="../../assets/images/cards/etiquetas.jpg"  
                                >
                                </v-img>
                                <div class="capa"></div>
                            </div>
                        </div>   
                    </a>
                </v-col>
                
                <v-col
                    align="center"
                    justify="center"
                    cols="10"
                    sm="5"
                    md="3"
                    lg="2"
                >   
                    <a href="#etiquetas_especiales">
                        <div class="card mb-5">
                            <h1 class="titulo_card text-uppercase mb-3">Etiqueta Especial</h1>
            
                            <div class="img_card">
                                <v-img class="img"
                                    src="../../assets/images/cards/especiales.jpg"
                                >
                                </v-img>
                                <div class="capa"></div>
                            </div>
                        </div>
                    </a>
                </v-col>
                
                <v-col
                    align="center"
                    justify="center"
                    cols="10"
                    sm="5"
                    md="3"
                    lg="2"
                >
                    <a href="#hardware_software">
                        <div class="card mb-5">
                            <h1 class="titulo_card text-uppercase mb-3">Hardware / Software</h1>
            
                            <div class="img_card">
                                <v-img class="img"
                                src="../../assets/images/cards/hardware.jpg"
                                >
                                </v-img>
                                <div class="capa"></div>
                            </div>
                        </div>
                    </a>
                </v-col>
                
                <v-col
                    align="center"
                    justify="center"
                    cols="10"
                    sm="5"
                    md="3"
                    lg="2"
                >
                    <a href="#proyectos_integrales">
                        <div class="card mb-5">
                            <h1 class="titulo_card text-uppercase mb-3">Integración de proyectos</h1>
            
                            <div class="img_card">
                                <v-img class="img"
                                src="../../assets/images/cards/proyectos.jpg"
                                >
                                </v-img>
                                <div class="capa"></div>
                            </div>
                                
                        </div> 
                    </a>     
                </v-col>

                <v-col
                    align="center"
                    justify="center"
                    cols="10"
                    sm="5"
                    md="3"
                    lg="2"
                >
                    <a href="#etiquetas_rfid">
                        <div class="card mb-5">
                            <h1 class="titulo_card text-uppercase mb-3">Sistemas RFID</h1>
            
                            <div class="img_card">
                                <v-img class="img"
                                src="../../assets/images/cards/rfid.jpg"
                                >
                                </v-img>
                                <div class="capa"></div>
                            </div>
                                
                        </div> 
                    </a>     
                </v-col>
            </v-row>           
        </v-container>
    </section>
</template>

<style lang="scss">

    #section_intro{
        .cont_btn_inicio{
            margin-top: -10%;
        }
        .card{
            width: 100%;

            .img_card{
                width: 100%;
                overflow: hidden;
                border-radius: 14px;                
                position: relative;

                .img{
                    display: block;
                }
            }  
            
            .capa {
                position: absolute;
                top: 0;
                bottom: 0;
                left: 0;
                right: 0;
                height: 100%;
                width: 100%;
                opacity: 0;
                transition: .5s ease;
                background-color: var(--azul-oscuro);
            }

            .img_card:hover .img{
                transform: scale(1.2) !important;              
            }

            .titulo_card:hover{
                font-weight: 700 !important;
                color: var(--negro) !important;
            }

            .img_card:hover .capa {
                opacity: 0.6;
            }              
        }        
    }

</style>