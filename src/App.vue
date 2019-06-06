<template>
  <div id="app">
    <appHeader></appHeader>
    <appTalents></appTalents>
    <appImg></appImg>
  </div>
</template>

<script>
import header from './components/header.vue';
import talents from './components/talents.vue';


export default {
  name: 'app',
  components: {
    appHeader:header,
    appTalents:talents,
  },
  data() {
    return {

    }
  }
}
</script>

<style>
#app {
  font-family: 'Norwester', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  text-align: center;
  color: black;
  margin-top: 60px;
  background-image: url("./assets/cupcoffeeclair.png");
  background-repeat: no-repeat;
  background-position: center; 
  
}
</style>
