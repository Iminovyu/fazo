<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <h1>Hello World <span>s</span></h1>
</template>

<style scoped lang="scss">
$bgColor: salmon;
h1{
  font-family: sans-serif;
  background-color: $bgColor;
  span{
    color: red;
  }
}
</style>
