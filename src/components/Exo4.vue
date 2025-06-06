<script setup>
import { ref } from 'vue';
const name = ref('');

const isActive = ref(true);

</script>

<template>

    <br>
    <input v-model="name" type="text">
    <br>
    <p :class="{active: isActive}">je m'appelle {{  name }}</p>
</template>

<style></style>