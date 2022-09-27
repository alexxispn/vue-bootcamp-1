<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <Counter :start="100" title="Hola Mundo" /> -->

  <IndecisionGame/>
</template>

<script>
// import TheCounter from "@/components/TheCounter";
import IndecisionGame from "@/components/IndecisionGame";

export default {
  name: 'App',
  components: {
    // TheCounter,
    IndecisionGame
  }
}
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
