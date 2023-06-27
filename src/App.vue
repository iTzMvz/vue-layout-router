<script setup>
import { RouterView } from 'vue-router'

// import HomeView from '@/views/HomeView.vue'
// import AboutView from './views/AboutView.vue'
</script>

<template>
  <header>HEADER</header>
  <aside>
    <nav>
      <router-link to="/">Home</router-link>
      <router-link to="/about">Sobre</router-link>
    </nav>
  </aside>
  <main>
    <RouterView />
    <!-- <home-view/>
    <AboutView/> -->
  </main>
  <footer>FOOTER</footer>
</template>

<style scoped>
nav{
  display: flex;
  flex-direction: column;
  gap: 1rm;
}
</style>
