<template>
    <v-img
        aspect-ratio="16/9"
        cover
        src="@/assets/Cover.jpg"
    >

        <v-container
        fluid
        >
            <v-row style="height: 80px"></v-row>
            <v-row justify="center">
                <v-avatar
                    rounded="1"
                    size="250"
                >
                    <v-img src="@/assets/Avatar.png" ></v-img>
                </v-avatar>
            </v-row>
            <v-row justify="center">
                <h1>
                    Marie Brunetto
                </h1>
            </v-row>
            <v-row justify="center">
                <v-col cols="3"></v-col>
                
                <v-col>
                    <p>
                    Je suis étudiante en avant dernière année de diplôme d'ingénieur en Informatique et Réseaux à l'INSA Toulouse
                    <br>
                    Passionée par le développement en général, particulièrement vidéo ludique 
                    </p>
                </v-col>
                <v-col cols="3"></v-col>
            </v-row>
            <!--
            <v-row>
                <v-btn class="CV-btn" rounded="xl" height="80" variant="flat" :href='generateUrlCV()'>
                    <v-icon size="50">mdi-download</v-icon> Télécharger mon CV
                </v-btn>
            </v-row>
            -->
        </v-container>
        
    
    
    </v-img>
</template>

<script lang="ts" setup>
    
    const generateUrlCV = function() {
        return new URL(`/src/assets/CV_FR_2024_Alternance.pdf`, import.meta.url).href
    }
</script>


<style scoped>
    h1{
        font-size: 50px;
        font-family: BerlinX-Bold;
    }
    
    p{
        font-size: 30px;
        text-align: center;
        font-family: Berlin-Bold;

    }

    .CV-btn{
        background-color:var(--PepoRed2);
        color:var(--PepoWhite);
        margin:0 auto;
        padding-left: 30px;
        padding-right: 30px;
        margin-top:20px;
    }
</style>