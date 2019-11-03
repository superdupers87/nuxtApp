<template>
  <div class="bg">
    <div class="container mt-5 mb-5">
      <div>
        <h1 class="title">AppApricot</h1>
        <h2 class="subtitle">My riveting Nuxt.js project</h2>
        <div class="links">
          <!-- <a href="https://nuxtjs.org/" target="_blank" class="button--green">Documentation</a>
          <a href="https://github.com/nuxt/nuxt.js" target="_blank" class="button--grey">GitHub</a>-->
        </div>
      </div>
    </div>
    <i class="fab fa-facebook"></i>
    <product-image />
  </div>
</template>

<style scoped>
.bg {
  background-image: url("../assets/mt-2.svg");
  background-size: cover;
  height: 100vh;
}

.container {
  margin: 0 auto;
  min-height: 30vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: var(--color-turqouise);
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: var(--color-pink);
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

<script>
import ProductImage from "~/components/ProductImage.vue";

export default {
  components: {
    ProductImage
  }
};
</script>

