<template>
  <h1> {{ titulo}} </h1>
  <button>Apretame</button>
  <input type="text" ref="caja">
</template>

<script>

export default {
  name: "App",
  data() {
    return {
      titulo:'Agarrala Zamorano!'
    }
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
