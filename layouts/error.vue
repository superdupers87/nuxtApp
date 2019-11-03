<template>
  <div class="container">
    <h1 v-if="error.statusCode === 404">Page not found</h1>
    <h1 v-else>An error occurred</h1>
    <div class="links">
      <button type="button" class="btn btn-outline-primary">
        <nuxt-link to="/">Home page</nuxt-link>
      </button>
    </div>
  </div>
</template>

<style scoped>
h1 {
  color: #35495e;
}
.links {
  display: grid;
  grid-template: auto;
}
</style>


<script>
export default {
  props: ["error"],
  layout: "default" // you can set a custom layout for the error page
};
</script>