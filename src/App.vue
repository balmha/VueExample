<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png">
    <Gallery/>
  </div>
</template>

<script>
import Gallery from "./components/Gallery";

export default {
  name: "App",
  components: {
    Gallery
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
