<template>
    <section id="section_banner" class="w-100 ">   
        <video class="video_vertical" src="../../assets/videos/hero_vertical.mp4" autoplay playsinline muted loop ></video>
        <video class="video_horizontal" src="../../assets/videos/hero_horizontal.mp4" autoplay playsinline muted loop ></video>  
    </section>
</template>

<style lang="scss">
   
    #section_banner{
        margin-top: 56px;
        width: 100vw;
        height: auto;
        position: relative;
        overflow: hidden;
        
        video{
            
            width: 100%;
            height: 100%;     
        }

        .video_horizontal{
            display: none;
        }
    }


</style>