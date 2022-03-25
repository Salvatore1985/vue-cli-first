<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <myApp />
  </div>
</template>

<script>
import myApp from "./components/myApp.vue";

export default {
  name: "App",
  components: {
    myApp,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
