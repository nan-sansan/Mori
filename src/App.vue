<script setup>
import { RouterLink, RouterView } from 'vue-router'
import PageHeader from '../src/components/PageHeader.vue'
import HomeView from './views/HomeView.vue';
import PageFooter from './components/PageFooter.vue';
</script>

<template>
    <nav>
      <PageHeader/>
    </nav>
    <HomeView/>
    <PageFooter/>
</template>

<style scoped>

</style>
