<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header class="header">
    <a href="#" class="logo">M JABIR</a>
    <div class="bx bx-menu" id="menu-icon"></div>
    <nav class="navbar">
      <router-link to="/home" exact-active-class="active">Home</router-link>
      <router-link to="/about" exact-active-class="active">About</router-link>
      <router-link to="/education" exact-active-class="active">Education</router-link>
      <router-link to="/skills" exact-active-class="active">Skills</router-link>
      <router-link to="/projects" exact-active-class="active">Projects</router-link>
      <router-link to="/contact" exact-active-class="active">Contact</router-link>
    </nav>
  </header>
</template>
