<template>
  <div class="main">
    <div class="split left">
      <div class="centered">
        <h2>About</h2>
      </div>
    </div>

    <div class="split right">
      <div class="centered">
        <h2>Chat</h2>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "LandingPage"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.split {
  height: 100%;
  overflow-x: hidden;
  position: fixed;
}
.left {
  left: 0;
  background-color: #fafafa;
  width: 30%;
}
.right {
  right: 0;
  background-color: #ececec;
  width: 70%;
  float: right;
}
</style>
