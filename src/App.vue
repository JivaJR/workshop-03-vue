<script setup>
  import SideBar from './components/SideBar.vue';
  import TopBar from './components/TopBar.vue';
  import ViewHome from './components/ViewHome.vue';
  import './style.css'
</script>

<template>
  <header>
    <TopBar/>
  </header>
  <main class="peak">
    <SideBar/>
    <ViewHome/>
  </main>
</template>
<style scoped>
.peak{
  display: flex;
}
</style>

