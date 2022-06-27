<template>
  <div id="app">
    <nav>
      <router-link to="/">Homepage</router-link> |
      <router-link to="/about">About Me</router-link> |
      <router-link to="/contact">Contact</router-link>
    </nav>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: black;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: black;

    &.router-link-exact-active {
      color: crimson;
    }
  }
}
</style>
