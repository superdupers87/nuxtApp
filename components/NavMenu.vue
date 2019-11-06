<template>
  <div>
    <nav class="navbar navbar-expand navbar-light bg-light pl-5">
      <logo />
      <ul class="nav navbar-nav">
        <li class="nav-item active">
          <a class="nav-link" href="#">
            Treatments
            <span class="sr-only">(current)</span>
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
    </nav>
  </div>
</template>
<style scoped>
.navbar {
  background-color: #fec2a7 !important;
}
a.nav-link {
  color: #fff !important;
}
a.nav-link:hover {
  color: var(--color-turqouise);
}
</style>
<script>
import Logo from "~/components/Logo.vue";

export default {
  components: {
    Logo
  }
};
</script>