<template lang="pug">
h1 {{ message }}
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  data() {
    return {
      message: "Hello",
    };
  },
};
</script>

<style lang="scss">
h1 {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: red;
  // color: #2c3e50;
  margin-top: 60px;
}
</style>
