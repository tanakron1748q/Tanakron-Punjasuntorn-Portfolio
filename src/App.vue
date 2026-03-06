<script setup>
import { RouterView } from 'vue-router'
import Footer from './components/Footer.vue'
</script>

<template>
  <div class="layout">
    <RouterView />
    <Footer />
  </div>
</template>

<style>

  body {
      margin: 0;
      background-color: rgb(249, 248, 246);
  }


  .layout { 
    min-height: 100vh;
    display: flex;
    flex-direction: column;
  }

  .layout > :first-child {
    flex: 1;
  }

</style>