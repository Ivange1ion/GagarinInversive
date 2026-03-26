<script setup>
import Header from "./components/Header/Header.vue";
import Hero from "./components/Hero/Hero.vue";
import Poster from "./components/Poster/Poster.vue";
import Modal from "./components/UI/Modal.vue";
import Advantages from "./components/Advantages/Advantages.vue";
import About from "./components/About/About.vue";
</script>

<template>
  <Header><Modal></Modal></Header>
  <Hero></Hero>
  <Poster></Poster>
  <About />
  <Advantages />
</template>