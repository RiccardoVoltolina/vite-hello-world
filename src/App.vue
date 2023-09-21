<script>
  import Jumbotron from "./components/appHero.vue"
  import Title from "./components/title.vue"
  export default{
    // questo é il vs options object
    data() {
      return {
        message: 'Hello Vite!',

      }
    },
    components: {
      Title,
      Jumbotron,
    },
  }
</script>

<template>
  <h1>{{ message }}</h1>
  <Title></Title>
  <Jumbotron></Jumbotron>
   
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
