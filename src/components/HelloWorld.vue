<script setup>
import { ref } from 'vue'

const count = ref(0)
console.log(count.value) // 0
</script>

<template>
  <div>
    <h1>Home</h1>
    <p>Count: {{ count }}</p>
    <button @click="count++">Increment</button>
  </div>
</template>