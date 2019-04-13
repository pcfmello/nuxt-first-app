<template>
  <section class="container">
    <h1>About our Nuxt</h1>
    <p class="subheading">They're juicy and stuff.</p>

    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
  </section>
</template>

<script>
export default {
  head() {
    return {
      title: "About Nuxt First App",
      meta: [
        { name: "description", content: "This is my about description here." },
        { name: "keywords", content: "about nuxt, nuxt info" }
      ]
    };
  }
};
</script>

<style>
</style>
