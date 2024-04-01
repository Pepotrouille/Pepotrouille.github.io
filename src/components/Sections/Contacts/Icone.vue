<template>
    <div class="text-center">
        <v-tooltip
          location="top center"
          origin="auto"
          no-click-animation
        >
            <template v-slot:activator="{ props }">
                <v-btn v-bind="props" class="Icone" size="80" rounded="circle" :href="link" target="_blank">
                    <v-avatar size="80">
                        <v-img :src='"/src/assets/Icones/Icone_" + pathName + ".png"' />
                    </v-avatar>
                </v-btn>
            </template>

            <div class="hoverDiv">{{ hoverName }}</div>
        </v-tooltip>
  </div>
        
    
</template>


<script lang="ts" setup>
    //Variables
    defineProps(['pathName', 'hoverName', 'link'])
    // 
</script>

<style scoped>
    .Icone{
        margin-left: 10px;
        margin-right: 10px;
    }
    .Icone:hover{
        
        background-color: #fdbe76;
    }
    .hoverDiv{
        color: #fefaf0;
    }
</style>