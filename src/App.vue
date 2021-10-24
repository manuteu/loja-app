<template>
  <div id="app">
    <Header />
    <FilmList class="flatlist" />
    <div id="load"></div>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import FilmList from "./components/FilmList.vue";

export default {
  name: "App",
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
#load {
  width: 60px;
  height: 60px;
  border: 10px solid;
  border-radius: 50%;
  border-top-color: transparent;
  margin: 0 auto;
  color: #dfe6ed;
  margin-bottom: 80px;
  animation: load 0.8s linear infinite;
}

@keyframes load {
  to {
    transform: rotate(360deg);
  }
}
.filmlist {
  top: 70px;
}
</style>
