<script setup>
import pezao from './components/pezao.vue'
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
