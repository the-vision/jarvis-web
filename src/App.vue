<template>
    <div id="app">
        <GithubCorner url='https://github.com/the-vision/jarvis-web'
                      :size='70' gitColor='#fff' cornerColor='#20639b' flipOnHover />
        <Navigation/>
        <!-- <div id="nav">
            <router-link to="/">Home</router-link> |
            <router-link to="/about">About</router-link>
        </div> -->
        <router-view />
        <Footer/>
    </div>

</template>

<script>
    import GithubCorner from 'vue-github-corners';
    import Footer from './components/Footer';
    import Navigation from './components/Navigation';
    export default {
        name: "App",
        components: {
            GithubCorner,
            Footer,
            Navigation
        }
    };
</script>
<style>

    #app {
        font-family: Avenir, Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
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