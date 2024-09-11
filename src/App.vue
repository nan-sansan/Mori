<script setup>
import { RouterLink, RouterView } from 'vue-router'
import PageHeader from '../src/components/PageHeader.vue'
</script>

<template>
  <header>
    <PageHeader/>
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
  </header>

  <RouterView />
</template>

<style scoped>

</style>
