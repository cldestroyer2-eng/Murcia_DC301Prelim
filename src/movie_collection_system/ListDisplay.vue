<script setup>

import {ref} from 'vue'

const movies = ref([
    'Encanto', 'Elemental', 'Book of Life', 'Avengers', 'Avatar: Fire and Ashes'
])

</script>

<template>

<div>
    <h1>Movies</h1>
    <ul>
        <li v-for="movie in movies">{{ movie }}</li>
    </ul>
</div>
</template>