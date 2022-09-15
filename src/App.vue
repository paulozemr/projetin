<script setup>
import HeaderVue from './components/Header.vue';
import { RouterLink, RouterView } from 'vue-router'
import Pezao from './components/pezao.vue'
</script>

<template>
<HeaderVue></HeaderVue>
<RouterView></RouterView>
<Pezao></Pezao>
</template>

<style scoped>

</style>
