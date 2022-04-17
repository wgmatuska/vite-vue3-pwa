<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
  secondmsg: String,
  thirdmsg: String
})

const count = ref(0)
</script>



<template>
  <p>{{ msg }}</p>

  <p>{{ secondmsg }}</p>

  <p>
    Just some text in a paragraph.
  </p>

  <button type="button" @click="count++">count is: {{ count }}</button>
  <p>{{ thirdmsg }}</p>
</template>



<style scoped>
a {
  color: #42b983;
}
</style>
