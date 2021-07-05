<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/portfolio">Portfolio</router-link>
  </div>
  <router-view/>
  <Footer />
</template>

<script>

import Footer from "./components/Footer/Footer.vue";

export default {
  name: 'App',
  components: {Footer}
}
</script>

<style>
@import './styles/reset.css';

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: flex;
  align-items: center;
  flex-direction: column;
  background-color: beige;
  height: 100vh;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
