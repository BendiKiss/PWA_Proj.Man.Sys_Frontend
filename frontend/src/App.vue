<template>
  <div id="nav">
    <Nav></Nav>
  </div>
  <router-view/>
</template>

<script>
import Nav from './components/Nav.vue'

export default {
  name: 'App',
    components: {
      Nav
    }
}
</script>

<style lang="scss">

#app {
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
    color: #ffffff;

    &.router-link-exact-active {
      color: #ffbb00;
    }
  }
}
</style>
