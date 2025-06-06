<script setup>
import { ref } from 'vue';

const fruits = ref(['pomme', 'poire', 'banane'])

</script>

<template>
    <ul>
        <li v-for="fruit in fruits">{{ fruit }}</li>
    </ul>
</template>

<style></style>