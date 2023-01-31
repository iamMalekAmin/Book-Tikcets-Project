<script setup>
import Header from "./components/Header.vue";
import Home from "./components/Home.vue";
import Section2 from "./components/Section2.vue";
import Section3 from "./components/Section3.vue";
import Section4 from "./components/Section4.vue";
import Section5 from "./components/Section5.vue";
import Section6 from "./components/Section6.vue";
import Sitefooter from "./components/Sitefooter.vue";
</script>

<template>
  <header>
    <Header />
  </header>

  <main>
    <Home />
    <Section2 />
    <Section3 />
    <Section4 />
    <Section5 />
    <Section6 />
  </main>
  <footer>
    <Sitefooter />
  </footer>
</template>

<style scoped>
</style>
