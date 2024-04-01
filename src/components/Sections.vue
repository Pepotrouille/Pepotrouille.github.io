<template>
    <v-container style="padding-bottom: 300px;">
        <v-responsive>
            <v-row>
                <SectionTitle title="Competences"/>
            </v-row>
            <v-row>
                <Competences/>
            </v-row>
            <v-row>
                <SectionTitle title="Projets"/>
            </v-row>
            <v-row>
                <Projets />
            </v-row>
            <v-row>
                <SectionTitle title="Experiences"/>
            </v-row>
            <v-row>
                <div style="margin:0 auto; font-size:20px; font-weight: 1000;">
                    Bientôt
                </div>
            </v-row>
            <v-row>
                <SectionTitle title="Education"/>
            </v-row>
            <v-row>
                <div style="margin:0 auto; font-size:20px; font-weight: 1000;">
                    Bientôt
                </div>
            </v-row>
            <v-row>
                <SectionTitle title="Contact"/>
            </v-row>
            <v-row>
                <Contacts />
            </v-row>
        </v-responsive>
    </v-container>
</template>


<script setup lang="ts">
  import Contacts from '@/components/Sections/Contacts/Main.vue'
  import Projets from '@/components/Sections/Projets/Main.vue'
</script>