<template>
  <div id="navbar-app">
    <div id="nav">
      <router-link to="/vueapp1">vueapp1</router-link> |
      <router-link to="/vueapp2">vueapp2</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
#navbar-app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
