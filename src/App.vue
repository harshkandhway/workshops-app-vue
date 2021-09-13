<template>

  <div id="app">
    <app-navbar></app-navbar>
    <div class="container"></div>
    <router-view></router-view>
    </div>
</template>

<script>
import Navbar from './components/Navbar'; 
export default {
  name: "App",
  components: {
    AppNavbar: Navbar
  }
};
</script>

<style scoped>

</style>
