<template>
  <div id="app">
    <Index />
    <HomePage />
  </div>
</template>

<script>
import Index from "./components/index.vue";
import HomePage from "./components/homePage.vue";

export default {
  name: "App",
  components: {
    Index,
    HomePage,
  },
};
</script>

<style>
html {
  font-family: BlinkMacSystemFont, -apple-system, "Segoe UI", "Roboto", "Oxygen",
    "Ubuntu", "Cantarell", "Fira Sans", "Droid Sans", "Helvetica Neue",
    "Helvetica", "Arial", sans-serif;
}
</style>
