<template>
    <v-container>
        <v-responsive>
            <CompetenceTitle title="Langages de Programmation"/>
            <v-row class="SkillCategory">
                <CompetenceIcone pathName="Langage_C" hoverName="C"/>
                <CompetenceIcone pathName="Langage_CSharp" hoverName="C#"/>
                <CompetenceIcone pathName="Langage_Python" hoverName="Python"/>
                <CompetenceIcone pathName="Langage_Java" hoverName="Java"/>
                <CompetenceIcone pathName="Langage_JS" hoverName="JavaScript"/>
            </v-row>
            <CompetenceTitle title="Logiciels Graphiques"/>
            <v-row class="SkillCategory">
                <CompetenceIcone pathName="Graphique_Illustrator" hoverName="Illustrator"/>
                <CompetenceIcone pathName="Graphique_Aseprite" hoverName="Aseprite"/>
                <CompetenceIcone pathName="Graphique_Procreate" hoverName="Procreate"/>
            </v-row>
            <CompetenceTitle title="Moteurs de Jeux"/>
            <v-row class="SkillCategory">
                <CompetenceIcone pathName="JV_Godot" hoverName="Godot"/>
                <CompetenceIcone pathName="JV_Unity" hoverName="Unity"/>
                <CompetenceIcone pathName="JV_Renpy" hoverName="Ren'Py"/>
                
            </v-row>
            <CompetenceTitle title="Langues"/>
            <v-row class="SkillCategory">
                <CompetenceIcone pathName="Langue_Francais" hoverName="Français : Maternel"/>
                <CompetenceIcone pathName="Langue_Anglais" hoverName="Anglais : Professionnel"/>
                <CompetenceIcone pathName="Langue_Italien" hoverName="Italien : Conversationnel"/>
                <CompetenceIcone pathName="Langue_Allemand" hoverName="Allemand : Notions"/>
            </v-row>
            <v-row style="margin-bottom:10px;"/>
            
        </v-responsive>
    </v-container>


</template>


<style scoped>
    .SkillCategory{
        justify-content: center;
    }
</style>
