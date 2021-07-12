<template>
  <div id="nav">
    <router-link to="/" class="nav">Home</router-link> 
    <router-link to="/about" class="nav">About</router-link> 
    <router-link to="/portfolio" class="nav">Portfolio</router-link>
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
  background-color:rgb(13, 9, 46);
  height: 100vh;
  color: #ffffff;
}

#nav {
  padding: 30px;
}

.nav{
  margin-left: 30px;
}

#nav a {
  font-weight: bold;
  color: #fdfeff;
}

#nav a.router-link-exact-active {
  color: #3590bb;
}
</style>
