<template>
  <div id="app">
    <Title />
    <Hero />
    
  </div>
</template>

<script>
import Hero from "./components/Hero.vue";
import Title from "./components/Title.vue";
export default {
  name: "App",
  components: {
    Title,
    Hero
  },
};
</script>

<style>
#app {
  margin: auto;
  display: flex;
  flex-direction: column;
}

/* RESET */

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  text-align: center;
}


</style>
