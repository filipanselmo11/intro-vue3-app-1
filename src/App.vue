<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <novo-component></novo-component>
</template>

<script>
import NovoComponent from './components/NovoComponent.vue';
export default {
  name: "App",
  components: {NovoComponent},
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
