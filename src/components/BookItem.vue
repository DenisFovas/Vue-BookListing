<template>
  <li>{{ book.title }}: {{ book.author }}</li>
</template>

<script>
export default {
  name: "BookItem",
  props: {
    book: {
      type: Object,
    },
  },
};
</script>

<style scoped></style>
