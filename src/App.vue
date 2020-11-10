<template>
  <div id="app">
    <img src="./assets/logo.png" />
    <book-list />
  </div>
</template>

<script>
import BookList from "./components/BookList";

export default {
  name: "app",
  components: {
    BookList,
  },
};
</script>

<style></style>
