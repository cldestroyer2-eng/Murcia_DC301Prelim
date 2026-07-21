<script setup>

import { ref } from 'vue'

const display = ref([
    'Movie Title', 'Genre','Year','Rating'
]);
</script>

<template>

<div v-for="displays in display" :key="display">
    {{ displays }}
    
</div>
</template>

