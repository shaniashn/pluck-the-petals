<template>
 <MainPage />
</template>

<script>
import MainPage from './MainPage.vue';

export default {
  name: 'App',
  components: {
    MainPage
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
}

body {
  margin: 0;
}

ul {
  margin: 0;
  padding: 0;
}

li {
  list-style: none;
}

</style>
