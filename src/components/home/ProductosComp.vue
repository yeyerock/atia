<template>
    <section id="section_productos">
        <v-container>
            <v-row
                id="etiquetas_rfid"
                class="justify-center cont_fila reveal fade-left"
            >
                <v-col 
                    cols="10"
                    sm="4"                    
                >  
                    <v-img 
                        class="img_producto mx-auto"
                            position="center center"
                            src="../../assets/images/productos/rfid.jpg"
                    >
                    </v-img>
                </v-col>
                <v-col
                    sm="7"
                    md="7"
                    lg="5"
                >
                    <v-container>
                        <h1 class="titulo mb-3">Etiquetas RFID</h1>
                        <p class="texto text-justify mb-5">
                            Las etiquetas RFID (Radio Frequency Identification) son dispositivos que utilizan la tecnología de radiofrecuencia para transmitir información a través de una onda electromagnética. Estas etiquetas contienen un chip y una antena, y pueden ser colocadas en objetos o productos para su identificación y seguimiento.
                        </p>
                        <v-btn 
                            class="enlace"
                            text
                            color="blue"
                            to="/rfid"
                        >
                            Conoce más <v-icon class="mx-2">mdi-arrow-right</v-icon>                   
                        </v-btn>
                    </v-container>                    
                </v-col>
            </v-row>

            <v-row
                id="etiquetas_especiales"
                class="justify-center cont_fila reveal fade-right"
            >
                <v-col 
                    cols="10"
                    sm="4"
                    
                    order="sm-last"
                >
                    <v-img 
                        class="img_producto mx-auto"
                        src="../../assets/images/productos/especiales.jpg"
                    >
                    </v-img>
                </v-col>
                <v-col
                    sm="7"
                    md="7"
                    lg="5"                    
                >
                    <v-container>
                        <h1 class="titulo mb-3">Etiquetas especiales</h1>
                        <p class="texto text-justify mb-5">
                            Manejamos gran variedad de etiquetas para condiciones especificas, por ejemplo; etiquetas resistentes al calor, al agua, a la corrosión, etc.
                        </p>
                        <v-row 
                            class="justify-start"
                        > 
                            <v-col>
                                <v-btn 
                                    class=" boton_whats"          
                                >
                                    <a href="https://api.whatsapp.com/send?phone=5214441787150&text=Hola%20necesito%20información%20sobre%20etiquetas%20especiales" class="enlace_boton" target="_blank">Cotizar proyecto <v-icon class="mx-2">mdi-whatsapp</v-icon></a>
                                </v-btn>
                            </v-col>

                            <v-col>
                                <v-btn 
                                    class=" boton"                                                               
                                >
                                    <a class="enlace_boton" target="_blank" href="/catalogos/PORTFOLIO_etiquetas.pdf">Catálogo <v-icon class="mx-2">mdi-arrow-collapse-down</v-icon> </a>
                                </v-btn>
                            </v-col>
                        </v-row>
                    </v-container>                   
                </v-col>
            </v-row>

            <v-row
                id="etiquetas_blancas"
                class="justify-center cont_fila reveal fade-left"
            >
                <v-col 
                    cols="10"
                    sm="4"
                    
                >
                    <v-img 
                        class="img_producto mx-auto"
                        src="../../assets/images/productos/blanco.jpg"
                    >
                    </v-img>
                </v-col>
                <v-col
                    sm="7"
                    md="7"
                    lg="5"
                >
                    <v-container>
                        <h1 class="titulo mb-3">Etiquetas en blanco</h1>
                        <p class="texto text-justify mb-5">
                            Las etiquetas en blanco son etiquetas sin impresión que se utilizan para imprimir información personalizada. Estas etiquetas pueden ser de cualquier tipo, como etiquetas RFID o etiquetas no RFID, y pueden ser utilizadas en una variedad de aplicaciones, como la impresión de números de serie, códigos de barras, fechas de caducidad, etc.
                        </p>
                        <v-row 
                            class="justify-between"
                        > 
                            <v-col>
                                <v-btn 
                                class=" boton_whats"          
                                >
                                    <a href="https://api.whatsapp.com/send?phone=5214441787150&text=Hola%20necesito%20información%20sobre%20etiquetas%20en%20blanco" class="enlace_boton" target="_blank">Cotizar proyecto <v-icon class="mx-2">mdi-whatsapp</v-icon>           </a>
                                </v-btn>
                            </v-col>
                        </v-row>
                    </v-container>                   
                </v-col>
            </v-row>

            <v-row
                id="proyectos_integrales"
                class="justify-center cont_fila reveal fade-right"
            >
                <v-col 
                    cols="10"
                    sm="4"
                    
                    order="sm-last"
                >
                    <v-img 
                        class="img_producto mx-auto"
                         src="../../assets/images/productos/proyectos.jpg"
                    >
                    </v-img>
                </v-col>
                <v-col
                    sm="7"
                    md="7"
                    lg="5"
                >
                    <v-container>
                        <h1 class="titulo mb-3">Proyectos integrales</h1>
                        <p class="texto text-justify mb-5">
                            Desarrollamos proyectos que abarcan todas las fases necesarias para implementar un sistema de etiquetado completo en tu empresa/industria. Incluye desde la selección del tipo de etiqueta adecuado para cada aplicación, hasta la implementación de un sistema de impresión y lectura de etiquetas, pasando por la creación de una estrategia de gestión y seguimiento de la información contenida en las etiquetas.
                        </p>
                        <v-row 
                            class="justify-between"
                        > 
                            <v-col>
                                <v-btn 
                                    class=" boton_whats"          
                                >
                                    <a href="https://api.whatsapp.com/send?phone=5214441787150&text=Hola%20necesito%20información%20sobre%20proyectos%20integrales" class="enlace_boton" target="_blank">Cotizar proyecto <v-icon class="mx-2">mdi-whatsapp</v-icon>           </a>
                                </v-btn>
                            </v-col>
                        </v-row>
                    </v-container>                   
                </v-col>
            </v-row>

            <v-row
                id="hardware_software"
                class="justify-center cont_fila  reveal fade-left"
            >
                <v-col 
                    cols="10"
                    sm="4"
                    
                >
                    <v-img 
                        class="img_producto mx-auto"
                        src="../../assets/images/productos/hardware.jpg"
                    >
                    </v-img>
                </v-col>
                <v-col
                    sm="7"
                    md="7"
                    lg="5"
                >
                    <v-container>
                        <h1 class="titulo mb-3">Hardware/software</h1>
                        <p class="texto text-justify mb-5">
                            En nuestra empresa ofrecemos una amplia variedad de hardware y software de etiquetado para satisfacer las necesidades de cualquier industria. Ofrecemos impresoras de etiquetas de alta calidad que son duraderas y fáciles de usar, así como software de diseño de etiquetas personalizado para que pueda crear etiquetas con su propio diseño y contenido. Además, ofrecemos accesorios y suministros de etiquetado, como cintas, etiquetas y ribbons, para asegurar que siempre tenga lo que necesita para imprimir sus etiquetas. 
                        </p>
                        <v-row 
                            class="justify-between"
                        > 
                            <v-col>
                                <v-btn 
                                    class=" boton_whats"          
                                >
                                    <a href="https://api.whatsapp.com/send?phone=5214441787150&text=Hola%20necesito%20información%20sobre%20hardware%20y%20software" class="enlace_boton" target="_blank">Cotizar proyecto <v-icon class="mx-2">mdi-whatsapp</v-icon>           </a>
                                </v-btn>
                            </v-col>

                            <v-col>
                                <v-btn 
                                    class=" boton"                                                               
                                >
                                    <a class="enlace_boton" target="_blank" href="/catalogos/PORTFOLIO_hardware.pdf">Catálogo <v-icon class="mx-2">mdi-arrow-collapse-down</v-icon> </a>
                                </v-btn>
                            </v-col>
                        </v-row>
                    </v-container>                   
                </v-col>
            </v-row>

            <v-row
                id="etiquetas_impresas"
                class="justify-center cont_fila reveal fade-right"
            >
                <v-col 
                    cols="10"
                    sm="4"
                    
                    order="sm-last"
                > 
                    <v-img 
                        class="img_producto mx-auto"
                        src="../../assets/images/productos/impresas.jpg"
                    >
                    </v-img>
                </v-col>
                <v-col
                    sm="7"
                    md="7"
                    lg="5"
                >
                    <v-container>
                        <h1 class="titulo mb-3">Etiquetas Impresas</h1>
                        <p class="texto text-justify mb-5">
                            Somos fabricantes de etiquetas impresas, estas permiten imprimir información personalizada como el nombre del producto, la fecha de caducidad, el precio, entre otros.
                        </p>

                        <p class="texto text-justify mb-5">
                            Pueden ser producidas en diferentes materiales, como papel, poliéster, vinilo, entre otros, y pueden ser impresas en diferentes tamaños y formas. 
                        </p>

                        <v-row 
                            class="justify-between"
                        > 
                            <v-col>
                                <v-btn 
                                    class=" boton_whats"          
                                >
                                    <a href="https://api.whatsapp.com/send?phone=5214441787150&text=Hola%20necesito%20información%20sobre%20etiquetas%20impresas" class="enlace_boton" target="_blank">Cotizar proyecto <v-icon class="mx-2">mdi-whatsapp</v-icon>           </a>
                                </v-btn>
                            </v-col>
                        </v-row>
                    </v-container>                   
                </v-col>
            </v-row>

            <v-row
                id="barras"
                class="justify-center cont_fila  reveal fade-left"
            >
                <v-col 
                    cols="10"
                    sm="4"
                    
                >
                    <v-img 
                        class="img_producto mx-auto"
                        src="../../assets/images/productos/barras.jpg"
                    >
                    </v-img>
                </v-col>
                <v-col
                    sm="7"
                    md="7"
                    lg="5"
                >
                    <v-container>
                        <h1 class="titulo mb-3">Código de barras</h1>
                        <p class="texto text-justify mb-5">
                            Trabajamos con diferentes tipos de códigos de barras, incluyendo los códigos EAN, UPC y QR, ayudamos a las empresas a implementar sistemas de escaneo de códigos de barras para mejorar la eficiencia en la gestión de inventarios y reducir los errores. 
                        </p>
                        <p class="texto text-justify mb-5">
                            Además, tenemos experiencia en la creación de etiquetas de códigos de barras personalizadas para empresas, asegurando que se ajusten a sus necesidades específicas de etiquetado y cumplan con las normas y regulaciones aplicables. También asesoramos a empresas sobre cómo diseñar e imprimir etiquetas de códigos de barras para obtener los mejores resultados y evitar problemas comunes, como la falta de legibilidad o la pérdida de adhesión de la etiqueta.
                        </p>
                        <v-row 
                            class="justify-between"
                        > 
                            <v-col>
                                <v-btn 
                                    class=" boton_whats"          
                                >
                                    <a href="https://api.whatsapp.com/send?phone=5214441787150&text=Hola%20necesito%20información%20sobre%20códigos%20de%20barras" class="enlace_boton" target="_blank">Cotizar proyecto <v-icon class="mx-2">mdi-whatsapp</v-icon>           </a>
                                </v-btn>
                            </v-col>

                        </v-row>
                    </v-container>                   
                </v-col>
            </v-row>

            
        </v-container>       
    </section>
</template>

<style lang="scss">
    #section_productos{
        .cont_fila{
            padding-top: 90px;
        }

        .cont_fila:nth-child(6){
            padding-bottom: 90px;
        }       

        .img_producto{
            width: 85%;
            border-radius: 14px;
        }
    }
</style>