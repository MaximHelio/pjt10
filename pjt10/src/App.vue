<template>
  <div id="app">
    <router-view />
    <MovieList />
  </div>
</template>

<script>
import MovieList from "@/components/MovieList";

export default {
  data() {
    return {};
  },
  components: {
    MovieList
  }
};
</script>

<style>
html,
body {
  height: 100%;
  background: linear-gradient(to bottom right, #ff6b81, #8e44ad);
}
#app {
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  max-width: 1000px;
  box-shadow: 0 0 40px #333;
}
</style>
