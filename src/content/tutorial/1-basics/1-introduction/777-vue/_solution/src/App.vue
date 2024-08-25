<template>
  <div>{{ message }}</div>
  <h1>My name is {{ name }}</h1>
</template>

<script setup>
import { ref } from 'vue'

const message = ref('Hello vue!')
const name = ref('Lucas Yang')
</script>
