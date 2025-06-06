<script setup>
import { ref } from 'vue';

const isActive = ref(true);

</script>

<template>
    <p :class="{ active: isActive }">Texte dynamique</p>
    <button @click="isActive = !isActive">activez</button>
</template>

<style scoped>
.active {

    background-color: brown;
}
</style>