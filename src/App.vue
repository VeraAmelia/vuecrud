<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
// import NavbarPage from './components/NavbarPage.vue';
</script>

<template>
  <header>
    <!-- <NavbarPage /> -->
    <div class="wrapper">
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container-fluid">
      <RouterLink class="navbar-brand" to="/">Navbar</RouterLink>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <li><RouterLink class="nav-link active" to="/">Home</RouterLink></li>
        </li>
        <li class="nav-item">
          <li><RouterLink class="nav-link active" to="/event">book</RouterLink></li>
        </li>
        <!-- <li class="nav-item">
          <li><RouterLink class="nav-link active" to="/guest">Guest</RouterLink></li>
        </li> -->
      </ul>
    </div>
  </div>
</nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>
  /* @import '../assets/style/style.css'; */
</style>
