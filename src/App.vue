<template>
  <div id="app">
    <Viewer />
    <Editer />
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import Viewer from "./components/Viewer.vue"
import Editer from "./components/Editer.vue"

export default {
  name: "App",
  components: {
    Viewer,
    Editer
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
