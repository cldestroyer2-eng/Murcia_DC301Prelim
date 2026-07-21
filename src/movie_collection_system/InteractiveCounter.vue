<script setup>
import { ref } from 'vue'

const watchedMovies = ref(0)

const watch = () => {
  watchedMovies.value += 1
}

const undo = () => {
  if (watchedMovies.value > 0) {
    watchedMovies.value -= 1
  }
}
</script>

<template>
  <div>
    <h1>Availabillity</h1>
    
    <p>Watched Movies: {{ watchedMovies }}</p>
    <button type="button" @click="watch">Watch</button>
    <button type="button" @click="undo">Undo</button>
  </div>
</template>
