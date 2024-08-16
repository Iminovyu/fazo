<script setup>
import { RouterLink, RouterView } from 'vue-router'
import LineComponent from './components/LineComponent.vue';
import NavComponent from './components/NavComponent.vue';
</script>

<template>
    <RouterView>
        <LineComponent></LineComponent>
        <NavComponent></NavComponent>
    </RouterView>
</template>

<style scoped lang="scss">

</style>
