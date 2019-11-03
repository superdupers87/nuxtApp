<template>
  <div class="product-grid m-5">
    <div class="card-group">
      <div v-for="post in posts" :key="post.id" class="card">
        <img src class="card-img-top" alt />
        <div class="card-body">
          <h5 class="card-title">{{ post.title }}</h5>
          <p class="card-text">{{ post.summary }}</p>
          <p class="card-text">
            <small class="text-muted">Last updated {{ post.published }}</small>
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import posts from "../assets/services.json";

export default {
  name: "posts",
  data() {
    return { posts };
  }
};
</script>
<style scoped>
.card {
  background-color: var(--color-darker-blue);
  border-radius: var(--border-radius);
  color: var(--color-white);
  margin: 0.5rem;
}

.card:hover {
  background: #441cd0;
}

small.text-muted {
  color: var(--color-turqouise) !important;
}
.product-grid {
  /* max-width: 500px; */
  display: grid;
  /* grid-template: 500px; */
}
</style>
