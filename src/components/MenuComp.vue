<template>
    <header id="navbar" class="">
        <div class="logo mx-2">
			<router-link to="/"  >
				<img class="logo_menu "  src="../assets/images/internal/logo.png" >
			</router-link> 
		</div>		
		
		<ul class="links d-flex">
            <li v-on:click="cerrar()" class=" mx-3"><router-link class="enlace d-flex " to="/">Inicio</router-link> </li>
            <li v-on:click="cerrar()" class=" mx-3"><router-link class="enlace d-flex " to="/rfid">Conoce el RFID</router-link> </li>
		
			<div class="cont_redes d-flex justify-content-center mx-auto">
				<div class=" mx-2 "><a class="enlace d-flex" target="_blank" href="https://www.instagram.com/" ><v-icon class="icono">mdi-instagram</v-icon></a></div>
				<div class=" mx-2 "><a class="enlace d-flex" target="_blank"  href="https://api.whatsapp.com/send?phone=5214441787150&text=Hola%20necesito%20información%20sobre%20etiquetas"><v-icon class="icono">mdi-email-outline</v-icon></a></div>
            </div>
		</ul>
		
		<div class="toggle mx-2" v-on:click="abrir()">
			<div class="line1"></div>
			<div class="line2"></div>
			<div class="line3"></div>
		</div>
		
	</header>

</template>

<style lang="scss">
    #navbar {
        background: var(--turquesa);
        padding: 15px;
        width: 100vw;
        height: 65px;
        display: flex;
        align-items: center;
        justify-content: space-between;
        position: fixed;
        top: 0;
        left: 0;
        z-index: 3;
        overflow: hidden;

        .logo{
            
            .logo_menu{
                width: 7rem;
                height: auto;
            }
        } 

        .cont_redes{

            .icono{
                color: var(--blanco);
                font-size: 1.4rem;
            }
        } 

        .links{
            margin-right: 0;
            transition: 0.4s ease all, 0s ease background;
        }

        .enlace {
            padding: 0 15px;
            align-items: center;
            color: var(--blanco);
            transition: 0.4s ease all, 0s ease margin;
        }

        .enlace:hover,
        .icono:hover {
            color: var(--negro);
        }

        .toggle{
            display: none;
        }

        .sticky {
            position: fixed;
            z-index: 40;
        }

        .sticky ~ main {
            position: relative;
            z-index: 20;
            top: 65px;
        }
    }


    @media screen and (max-width: 1024px) {
        #navbar{
            .right {
                height: 0;
                overflow: hidden;
            }

            .toggle {
                position: absolute;
                top: 32.5px;
                right: 20px;
                z-index: 99;
                transform: translateY(-50%);
                cursor: pointer;
                width: 40px;
                height: 40px;
                display: flex;
                flex-direction: column;
                justify-content: center;
                align-items: center;
                overflow: hidden;
                transition: 0.3s;
            }

            .toggle > * {
                width: 80%;
                height: 2px;
                background: var(--blanco);
                margin: 3px 0;
                transition: 0.3s;
            }

            .links {
                position: fixed;
                background: var(--turquesa);
                z-index: 40;
                top: 0;
                left: -100%;
                flex-direction: column;
                width: 100vw;
                height: 100vh;
                li:first-child {
                    margin-top: 6rem;
                }
            }

            .enlace {
                text-align: left;
                height: 65px;
            }

            .cont_redes{
                margin-top: 1rem;

                .enlace{
                    .icono{
                        font-size: 1.5rem;
                    }
                } 
            }

            .sticky {
                position: fixed;
                z-index: 40;
            }

            &.collapsed{
            
                .toggle{
                    .line1 {
                        transform: rotate(-45deg) translate(-4px, 5px);
                        transition: 0.3s;
                    }
    
                    .line2 {
                        opacity: 0;
                        transition: 0.3s;
                    }
    
                    .line3 {
                        transform: rotate(45deg) translate(-5px, -6px);
                        transition: 0.3s;
                    }
                }

                .logo {
                    position: absolute;
                    z-index: 44;
                }        

                .links {
                    left: 0;

                    li {
                        width: 100%;
                    }                    
                }

                .right {
                    position: fixed;
                    width: 45vw;
                    text-align: center;
                    height: auto;
                    bottom: 40px;
                    left: 22.5vw;
                    transform: translateX(-50%);
                    z-index: 45;
                }  
                
                ~ main {
                    filter: blur(1px);
                    opacity: 0.8;
                }
            }
        } 
    }
</style>

<script>
    export default {
   
   methods: {
      abrir () {
        const navbar = document.querySelector('#navbar')
          navbar.querySelector('.toggle').addEventListener('click',()=>{          
          navbar.classList.toggle('collapsed')          
        })

        window.addEventListener('scroll',()=>{
          let windowY = window.pageYOffset
          let navbarHeight = document.querySelector('#navbar').offsetHeight
          if(windowY>navbarHeight) navbar.classList.add('sticky')
          else navbar.classList.remove('sticky')
        })
      },
      cerrar () {
        const navbar = document.querySelector('#navbar')
        navbar.classList.remove('collapsed')   
       
      }
    }
}
</script>