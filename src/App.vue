<script setup>
import PageHeader from '../src/components/PageHeader.vue'
import PageFooter from './components/PageFooter.vue';


</script>

<template>
    <PageHeader/>
    <div class="container">

        <RouterView></RouterView>
    </div>
    <PageFooter/>
</template>

<style scoped>
.container {
  margin: auto;
  width: 100%;
  height: 2000px;
  background-color: rgb(255, 236, 202);
}
</style>
