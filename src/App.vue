<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
import MySFC from './components/mySFC.vue'
import Joystick from './components/Joystick.vue'

</script>













<template>
  <HelloWorld msg="[msg parameter]" secondmsg="[secondmsg parameter]" thirdmsg="[thirdmsg parameter]" />
  <MySFC mynumber="6" />
  <Joystick @print="console.log('Clicked')" />
</template>













<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
