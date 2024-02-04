<template>
  <div>
    <button @click="increment">count: {{ count }}</button>
  </div>
</template>

<script>
import { ref } from 'vue'

const count = ref(0)
</script>