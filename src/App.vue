<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png"/>
    <jumbo/>
    <Title/>
  </div>
</template>

<script>
import Title from "./components/Title.vue";
import jumbo from "./components/jumpo.vue"

export default {
  components: { Title },
  name: "App",
  components: {
    Title,
    jumbo,
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
Title,img{
  z-index: 5;
}
jumbo{
  z-index: 0;
}    

</style>
