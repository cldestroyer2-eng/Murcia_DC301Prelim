<script setup>

import {ref} from 'vue'

const image = ref("https://play-lh.googleusercontent.com/-6ltLcICtfHeop4H5LxHeIIto1R8RutVVd8SUdG5xaP7Dg-s7pY7qAIWPg0E8Eo-he_MEHEe1_jZZx_-zT0B4jE")

</script>

<template>

<div>
    <br>
    <img :src="image" alt="Movie Collection" style="width: 100px; height: 100px;">
</div>

</template>