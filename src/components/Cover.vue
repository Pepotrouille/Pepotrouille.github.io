<template>
    <v-img
        aspect-ratio="16/9"
        cover
        src="@/assets/Cover.jpg"
    >

        <v-container
        fluid
        >
            <v-row style="height: 100px"></v-row>
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
        </v-container>
        
    
    
    </v-img>
</template>


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
</style>