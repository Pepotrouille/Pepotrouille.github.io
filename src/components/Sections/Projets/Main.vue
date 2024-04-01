<template>
    <v-card
      class="mx-auto"
      elevation="24"
      max-width="1100"
    >
        <v-carousel show-arrows="hover" style="max-width:1000px;">
            <Item title="L2Speak" description="L2 Speak est un jeu vidéo mobile destiné à l'apprentissage des langues. J'ai pu aider au développement à travers la création de décors dans une style pixel art ainsi que pour les traductions françaises." imageName="L2Speak" />
            <Item title="Jour de Neige" description="Réalisé sur Unity, Jour de Neige est un petit jeu d'énigme réalisé pour un Secret Santa. J'ai eu l'occasion de m'occuper seule de l'intégralité du projet, autant dans le développement que dans la partie graphique." imageName="Jour_De_Neige" />
            <Item title="Vox Populi" description="Vox Populi est un jeu indépendant de simulation politique développé par Velsin. J'ai eu la chance de créer une partie importante des animations et de l'UI." imageName="Vox_Populi" />
            <Item title="Zoomie" description="Zoomies a été réalisé lors de la Global Game Jam 2024, dans une équipe de 6. Il s'agit d'un petit jeu de puzzle sur le thème des chat dans la culture web. J'étais en partie en charge de la partie développement du projet." imageName="Zoomies" />
        </v-carousel>
    </v-card>
</template>


<script setup lang="ts">
  import Item from '@/components/Sections/Projets/Item.vue'
</script>