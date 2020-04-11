<template>
    <div id="app">
        <GithubCorner url='https://github.com/the-vision/jarvis-web'
                      :size='70' gitColor='#fff' cornerColor='#20639b' flipOnHover />
        <Navigation/>
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

   
</style>