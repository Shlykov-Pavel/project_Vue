<script setup>
import {ref} from 'vue'

const now = ref(new Date())
</script>

<template>
   <p> {{now.toLocaleDateString()}}</p>
</template>
