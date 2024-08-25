---
type: lesson
title: Vue.js 入門
template: vue
focus: /src/App.vue
---

# Vue.js 入門

```vue
<template>
  <div>{{ message }}</div>
  <h1>My name is {{ name }}</h1>
</template>

<script setup>
const message = ref('Hello vue!')
const name = ref('Lucas Yang')
</script>
```
