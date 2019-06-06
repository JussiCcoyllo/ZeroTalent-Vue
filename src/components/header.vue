<template>
  <header>
    <h2>{{principalTitle}}</h2>
    <hr>
    <hr>
    <h1>{{title}}</h1>
  </header>
</template>

<script>
  export default {
    data() {
      return {
        principalTitle: "10 things that require",
        title: "zero talent"
      }
    }
  }
</script>

<style>
  body {
    background-color: rgb(238, 198, 205);
  }
  h1, h2 {
    color: rgb(143, 41, 58);
    text-transform: uppercase; 
  }
  h2 {
    font-size: 40px;
    margin-bottom: 0;
  }
  h1 {
    font-size: 75px;
    margin-top: 0;
  }
  hr {
    width: 368px;
    color: black;
  }
</style>