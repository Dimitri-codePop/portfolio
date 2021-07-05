<template>
  <div class="home">
    <h1>{{msg}}</h1>
    <a href="/">Home</a> |
    <a href="/about">About</a> |
    <a href="/porfolio">Portfolio</a>
  </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<style scoped>
a {
  color: #42b983;
}
</style>
