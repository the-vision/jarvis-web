<template>
  <nav class="nav">
    <h1 class="nav-header">Jarvis</h1>
    <ul v-bind:class="[isActive ? 'nav-links' : 'nav-links active']">
      <li class="nav-link">
        <router-link to="/" class="link">Home</router-link>
      </li>
      <li class="nav-link">
        <router-link to="/about" class="link">About</router-link>
      </li>
      <li class="nav-link">
        <router-link to="#!" class="link">Projects</router-link>
      </li>
    </ul>
    <div class="burger" id="burger" @click="toggleClass()">
      <span class="line"></span>
      <span class="line"></span>
      <span class="line"></span>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navigation",
  data: function () {
    return {
      isActive: true,
    };
  },
  methods: {
    toggleClass: function () {
      this.isActive = !this.isActive;
    },
  },
};
</script>

<style scoped>
.nav {
  min-height: 10vh;
  background-color: #173f5f;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 1rem;
}
.nav-header {
  font-size: 2rem;
  color: #fff;
  margin-left: 2rem;
  flex: 0 0 1;
  padding: 1rem;
}

.nav-links {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 0rem 1rem;
  flex: 0 0 2;
  margin-right: 6rem;
}

.link:link,
.link:visited {
  color: #fff;
  text-decoration: none;
  text-transform: uppercase;
  letter-spacing: 2px;
}
.link:active,
.link:hover {
  color: rgb(165, 158, 158);
}
.burger {
  display: block;
  width: 1.5rem;
  height: 1.5rem;
  cursor: pointer;
  position: absolute;
  top: 1.4rem;
  right: 5rem;
  display: none;
}
.line {
  display: block;
  padding: 0.1rem 0rem;
  width: 1.4rem;
  margin: 0.3rem;
  background-color: #fff;
}

@media only screen and (max-width: 800px) {
  .burger {
    display: block;
  }
  .nav {
    flex-direction: column;
  }

  .nav-links {
    flex-direction: column;
    width: 100%;
    margin: 0;
  }

  .active.nav-links {
    display: none;
  }
}

@media only screen and (max-width: 400px) {
  .nav-header {
    font-size: 2rem;
    margin-left: 0.5rem;
    align-self: flex-start;
  }
}
</style>
