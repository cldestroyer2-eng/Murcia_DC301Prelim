<script setup>

import {ref} from 'vue'

const status = ref(true);

</script>

<template>

<div>
    <h1>Classification</h1>
    <p v-if="status == true">Available</p>
    <p v-else>Unavailable</p>
</div>
</template>