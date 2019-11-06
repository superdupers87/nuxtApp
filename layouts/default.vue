

<template>
  <div>
    <nav-menu />
    <nuxt />
  </div>
</template>

<style>
:root {
  --main-bg-color: #090863;
  --color-darker-blue: #010448;

  --color-turqouise: #86dffb;
  --color-purple: #7b6ef6;
  --color-pink: #de74f8;
  --color-white: #ffffff;

  --font-face: "Josefin Sans", sans-serif;
  --border-radius: 0.5rem;
}

html {
  font-family: var(--font-face);
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

body {
  background: #ffdead;
  font-family: var(--font-face);
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid var(--color-darker-blue);
  color: #fff;
  background: var(--color-darker-blue);
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: var(--color-darker-blue, 50%);
}

.button--grey {
  border-radius: 4px;
  border: 1px solid #fff;
  color: #fff;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
</style>

<script>
import NavMenu from "../components/NavMenu.vue";

export default {
  components: {
    NavMenu
  }
};
</script>