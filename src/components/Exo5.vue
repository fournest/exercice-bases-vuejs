<script setup>
import { ref } from 'vue';
const activeColor = ref('red')
const activeBackgroundColor = ref('lightblue')
const fontSize = ref(30)
const islooged = ref(true);
</script>

<template>

    <button @click="islooged = !islooged" :style="{ color : activeColor, fontSize : fontSize + 'px', backgroundColor : activeBackgroundColor }">connexion</button>
    <p v-if="islooged">Bienvenue utilisateur!</p>
    <p v-else :style="{fontSize : fontSize + 'px'}">Veuillez vous connecter</p>
</template>

<style>


</style>