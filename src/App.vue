<template>
  <div class="flex flex-col min-h-screen font-Roboto bg-weather-primary">
    <navbar/>
    <router-view/>
  </div>
</template>

<script setup>
import navbar from './components/SiteNavigation.vue'
</script>