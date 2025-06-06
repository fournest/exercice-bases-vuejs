<script setup>
import { ref } from 'vue';

const compteur = ref(0)

</script>

<template>
    <p>{{ compteur }}</p>
    <button @click="compteur++">Clique-moi!</button>
</template>

<style>


</style>