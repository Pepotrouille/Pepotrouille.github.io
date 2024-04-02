<template>
    <v-carousel-item
        color="rgb(1,64,41)"
        src="/src/assets/Decorations/Decoration_Cadre_Projet.png"
    >
    <div class="item">
    
        <img 
            :src='generateUrlImg(imageName)'
            
        />
        
        
        <h1>
            {{ title }}
        </h1>

        <p>
            
            {{ description }}
        </p>
    
    </div>
    </v-carousel-item>
    
</template>

<script lang="ts" setup>
    //Variables
    defineProps(['title', 'description', 'imageName'])
    // 
    const generateUrlImg = function(img: string) {
        return new URL(`/src/assets/Projets/Cover_${img}.png`, import.meta.url).href
    }
    
</script>


<style scoped>
    .item{
        align-items: center;
        padding-top:10%;
    }

    p, h1{
        color:var(--PepoWhite);
        text-align: center;
        margin:0 auto;
    }

    p{
        width:60%;
    }

    h1{
        width:80%;

    }

    img{
        display: block;
        width:80%;
        margin-left: auto;
        margin-right: auto;
    }
</style>