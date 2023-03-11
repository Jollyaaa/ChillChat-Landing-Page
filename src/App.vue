<template>
  <div id="app">
    <navBar />
    <jumboTron />
    <CTA />
    <cardsComp />
    <footerComp />
  </div>
</template>

<script>
import navBar from "./components/navBar.vue";
import jumboTron from "./components/jumboTron.vue";
import CTA from "./components/CTA.vue";
import cardsComp from "./components/cardsComp.vue";
import footerComp from "./components/footerComp.vue";

export default {
  name: "App",
  components: {
    navBar,
    jumboTron,
    CTA,
    cardsComp,
    footerComp,
  },
};
</script>

<style>
#app {
  font-family:Verdana, Geneva, Tahoma, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: justify;
  color: #000000;
  background-color: #82EEFD;
}
</style>
