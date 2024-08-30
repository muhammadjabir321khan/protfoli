<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navbar  from '../../components/partials/Navbar.vue'
import Home  from '../../components/Home.vue'
</script>
<template>
  <Navbar/>
  <RouterView />
</template>