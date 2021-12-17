<template>
  <div id="app">
    <Title />
    <img alt="Vue logo" src="./assets/jumbotron.jpg" />
  </div>
</template>

<script>

import Title from "./components/Title.vue";
export default {
  name: "App",
  components: {
    Title
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
