<template>
    <v-container>
        <v-responsive>
            <v-row class="SkillCategory">
                <Icone pathName="Reseaux_Linkedin" hoverName="LinkedIn" link="http://linkedin.com/in/marie-brunetto/"/>
                <Icone pathName="Reseaux_Behance" hoverName="Behance" link="https://www.behance.net/MariePepo"/>
                <Icone pathName="Reseaux_Itchio1" hoverName="Itch.io - Jeux et Game Jams" link="https://pepotrouille.itch.io/"/>
                <Icone pathName="Reseaux_Itchio2" hoverName="Itch.io - Pixel Art Assets" link="https://marie-pepo.itch.io/"/>
                <Icone pathName="Reseaux_Fiverr2" hoverName="Fiverr" link="https://www.fiverr.com/nekanos?up_rollout=true"/>
                <Icone pathName="Reseaux_Mail" hoverName="Mail to : marie.pepo.ei@gmail.com" link="mailto:marie.pepo.ei@gmail.com"/>
            </v-row>
            <v-row style="margin-bottom:10px;"/>
            
        </v-responsive>
    </v-container>
</template>


<script setup lang="ts">
  import Icone from '@/components/Sections/Contacts/Icone.vue'
</script>


<style scoped>
    .SkillCategory{
        justify-content: center;
        padding-top:15px;
        padding-bottom:15px;
    }
</style>