<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
<div style="max-width: 1200px; width: 100%;margin: auto;">
  <HelloWorld />
</div>
</template>

<style>
@import url(https://cdn.jsdelivr.net/npm/@mdi/font@6.6.96/css/materialdesignicons.min.css);
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

:root {
    --main-color:rgb(245, 61, 45);
    --sub-color:rgb(255, 102, 51);
}

.round{
  border-radius: 4px;
}
</style>
