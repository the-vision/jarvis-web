<template>
  <div id="app">
    <GithubCorner 
      url='https://github.com/the-vision/jarvis-web' 
      :size='70'  gitColor='#fff' cornerColor='#000' flipOnHover
     />
    <Navigation />
    <LandingPage />
  </div>
</template>

<script>
import Navigation from "./components/Navigation.vue";
import LandingPage from "./components/LandingPage.vue";
import GithubCorner from 'vue-github-corners'

export default {
  name: "App",
  components: {
    LandingPage,
    Navigation,
    GithubCorner 
  }
};
</script>

<style>
body,
html {
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0;
  padding: 0;
}
</style>
