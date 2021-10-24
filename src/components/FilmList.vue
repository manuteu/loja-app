<template>
  <section class="container filmlist" id="transform">
    <film-card />
    <film-card />
    <film-card />
    <film-card />
    <film-card />
    <film-card />
    <film-card />
    <film-card />
  </section>
</template>
<script>
import FilmCard from "./FilmCard.vue";
export default {
  name: "Header",
  components: {
    FilmCard,
  },
};

// window.addEventListener("scroll", ativaNoScroll);
</script>
<style scoped>
/*  */
</style>
