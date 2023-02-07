<script setup>
import { RouterLink, RouterView } from 'vue-router'
import FooterContent from './components/FooterContent.vue';

// import nav from 'bootstrap/dist/css/bootstrap.min.css'
// import nav from 'bootstrap/dist/css/bootstrap.css'
</script>

<template>
  <nav class ="navbar navbar-expand-lg custom-nav-bg-black sticky-top custom-bg-black" >
    <div class="container-fluid ">
      <RouterLink class="navbar-brand" to="/"><img src="./assets/img/logo1.png" class="img-thumbnail bg-transparent thumbnail" alt="LA Logo" style="margin-left:50px; max-height: 70px;"></RouterLink>
      <button class="navbar-toggler custom-toggler " type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <RouterLink class="nav-link active custom-nav-color custom-nav-text" aria-current="page" to="/cv">CV</RouterLink>
          <RouterLink class="nav-link custom-nav-color custom-nav-text" to="/">Portfolio</RouterLink>
          <RouterLink class="nav-link custom-nav-color custom-nav-text" to="/about">Contact</RouterLink>
        </div>
      </div>
    </div>
  </nav>

  <RouterView />

  <footer>
    <FooterContent />
  </footer>

</template>

<style>
  @import './assets/css/style.css';
  @import './assets/css/stylesheet.css';
</style>
