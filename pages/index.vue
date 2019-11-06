<template>
  <div class="bg">
    <div class="container mt-5 mb-5">
      <div>
        <h1 class="title">AppApricot</h1>
        <h2 class="subtitle">My riveting Nuxt.js project</h2>
        <div class="links"></div>
      </div>
    </div>
    <product-image />
  </div>
</template>

<style scoped>
.bg {
  background-image: url("../assets/mt-2.svg");
  background-size: cover;
  height: 100vh;
  background-color: navajowhite;
  background-blend-mode: overlay;
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
  color: #000;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #000;
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

