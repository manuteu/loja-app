<template>
  <div id="app" >
    <Header />
    <FilmList />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import FilmList from './components/FilmList.vue';

export default {
  name: 'App',
  components: {
    Header,
    FilmList,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
