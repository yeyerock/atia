<template>
    <section id="section_cuentanos">
        <v-container>
            <v-row
                class="justify-center align-center mb-5 mb-lg-10"
            >                
                <v-col
                    sm="7"
                    md="7"
                    lg="5"
                >
                    <v-container>
                        <h1 class="titulo mb-3">Cuéntanos sobre tu proyecto</h1>
                        <p class="texto text-justify mb-5">
                            Un RFID bien aplicado puede mejorar significativamente la eficiencia, la precisión y la seguridad de tu proyecto.
                        </p>
                        <p class="texto text-justify mb-5">
                            Cuéntanos tu proyecto para darte un vistazo al RFID y como puede aplicarse en tus procesos.
                        </p>
                        <v-btn 
                            class="boton"
                            text
                            dark
                        >
                            Agendar cita<v-icon class="mx-2">mdi-whatsapp</v-icon>                   
                        </v-btn>
                    </v-container>                    
                </v-col>
                <v-col 
                    cols="10"
                    sm="4"
                >
                <div class="img_cuentanos mx-auto mb-8 reveal fade-left">
                    <lottie-player src="https://lottie.host/709cd786-3f07-466d-97db-994ada5432e8/Wmwaxl0u0N.json" background="transparent" speed="1"  loop autoplay></lottie-player>
                </div>
                </v-col>
            </v-row>
        </v-container>
    </section>
</template>

<style lang="scss">

    #section_cuentanos{

        .img_cuentanos{
            width: 60%;
        }
    }

</style>