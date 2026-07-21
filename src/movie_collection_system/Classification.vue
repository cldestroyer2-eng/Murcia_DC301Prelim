<script setup>

import { ref, computed } from 'vue'

const movies = ref([
    'Encanto', 'Elemental', 'Book of Life', 'Avengers', 'Avatar: Fire and Ashes'
])


</script>

<template>
    <div>
        <h3 v-if="movies.value.length >= 5">Large Collection</h3>
        <h3 v-else>Small Collection</h3>
    </div>
</template>