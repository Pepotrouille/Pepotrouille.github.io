<template>
    <v-spacer/>
        <v-img class="Title-Decoration" src="@/assets/Decorations/Decoration_Titre_Gauche.png"  ></v-img>
                
            <div>
                {{ title }}
                
            </div>
        <v-img class="Title-Decoration" src="@/assets/Decorations/Decoration_Titre_Droit.png" ></v-img>
    <v-spacer/>
</template>



<script lang="ts" setup>
    //Variables
    defineProps(['title'])
    // 
</script>

<style scoped>
    
    div{
        padding-top: 30px;
        font-family: Broadway;
        font-size:50px;
        color:#fdbe76;
        height:150px;
    }

    .Title-Decoration{
        height:150px;

    }

</style>