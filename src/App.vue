<template>
  <div id="app">
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />
    <HelloWorld msg="Welcome to Your Vue.ts App!" />
  </div>

</template>

<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>



<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
