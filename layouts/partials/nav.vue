<template>
  <header>
    <nuxt-link to="/" class="logo">Nuxt First App</nuxt-link>
    <nav>
      <ul>
        <li>
          <nuxt-link to="/">Home</nuxt-link>
        </li>
        <li>
          <nuxt-link to="about">About</nuxt-link>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {};
</script>

<style>
header {
  background-color: rgb(0, 219, 146);
  display: grid;
  grid-template-columns: repeat(2, auto);
  padding: 8px;
}

.logo,
li a {
  padding: 1em 2em;
  display: block;
  text-transform: uppercase;
  text-decoration: none;
  font-weight: bold;
  color: white;
  font-size: 0.9em;
}

nav {
  justify-self: right;
}

ul {
  list-style-type: none;
}
li {
  display: inline;
}
li a {
  display: inline-block;
  background: rgba(0, 0, 0, 0.1);
}
</style>
