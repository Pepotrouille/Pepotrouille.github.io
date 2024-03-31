<template>
    <v-row style="padding-top:10px;">
        <v-col cols="2"/>
        <v-col class="colonne" >
            <v-divider :thickness="2" class="border-opacity-100" ></v-divider>
        </v-col >
            <h2>
                {{ title }}
            </h2>
        <v-col class="colonne">
            <v-divider :thickness="2" class="border-opacity-100" ></v-divider>
        </v-col>
        <v-col cols="2"/>
    </v-row>
</template>

<script lang="ts" setup>
    //Variables
    defineProps(['title'])
    // 
</script>
    
<style scoped>
    .border-opacity-100{
        color:#fdbe76;
        margin-top: 8px;
    }

    h2{
        
        color:#d6894a;
        height:50px;
        margin-left: 12px;
        margin-right: 12px;
    }
</style>