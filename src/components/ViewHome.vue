<script setup>
import NavBar from './NavBar.vue';
import WorksHome from './WorksHome.vue';

</script>

<template>
    <div class="peak flex flex-col absolute left-[90px]">
      <NavBar/>
      <WorksHome/>
    </div>
  </template>
  <style scoped>
  .peak{
    width: calc(100vw - 107px);
  }
  </style>