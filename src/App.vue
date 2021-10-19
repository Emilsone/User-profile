<template>
  <div id="app">
    <GetPage />
  </div>
</template>

<script>
import GetPage from "./components/GetPage.vue";

export default {
  name: "App",
  components: {
    GetPage,
  },
  
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap");

#app {
 font-family: "Open Sans", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
