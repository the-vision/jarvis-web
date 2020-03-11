<template>
  <div class="nav">
    <h3 class="header">Jarvis</h3>
    <span>
      <a href="#">Projects</a>
      <a href="#">Chat</a>
      <a href="#">About</a>
    </span>
  </div>
</template>
<script>
export default {
  name: "Navigation"
};
</script>
<style scoped>
.nav {
  height: 4em;
  background-color: #333;
  padding: 1em;
}
.header {
  color: #fff;
  float: left;
  margin: 0.5em;
  font-size: 2em;
}
.nav a {
  color: #fff;
  float: right;
  text-decoration: none;
  font-size: 1.5em;
  margin: 0.5em;
}
</style>
