<template>
  <h1 @click="increase">
    {{ count }} 
  </h1>
</template>

<script>
import { ref } from 'vue'

export default {
  setup() {
    let count = ref(0)
    function increase() {
      count.value += 1
    }

    return {
      count,
      increase
      }
    }
  }

</script>