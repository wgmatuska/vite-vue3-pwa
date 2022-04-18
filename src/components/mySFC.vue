<script setup>
import { ref } from 'vue'

defineProps({
  mynumber: String
})

const count = ref(0)
</script>



<template>
  <p>{{ mynumber }}</p>
</template>



<style scoped>
a {
  color: #42b983;
}
</style>
