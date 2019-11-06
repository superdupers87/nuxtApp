<template>
  <div class="product-grid m-5">
    <div class="card-group">
      <div v-for="post in posts" :key="post.id" class="card">
        <img :src="`${post.image}`" class="card-img-top p-3" alt />
        <div class="card-body">
          <h5 class="card-title">{{ post.title }}</h5>
          <p class="card-text">{{ post.summary }}</p>
          <div>{post.tags}</div>
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
  border-radius: var(--border-radius);
  color: #000;
  margin: 0.5rem;
  border-radius: 0.5rem !important;
  background: #fff;
}

img.card-img-top {
  mix-blend-mode: luminosity;
  height: 200px;
  object-fit: cover;
  border-top-left-radius: 0.5rem;
  border-top-right-radius: 0.5rem;
}

.card:hover {
  mix-blend-mode: darken;
  background: #a894ae;
  box-shadow: 0 0 black;
}

small.text-muted {
  color: #646363 !important;
}
.product-grid {
  /* max-width: 500px; */
  display: grid;
  /* grid-template: 500px; */
}
</style>
