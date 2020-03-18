<template>
    <div class="main">
        <About class="split" />
        <Chat class="split" />
    </div>
</template>

<script>

    import About from "../components/About.vue";
    import Chat from "../components/Chat.vue";

    export default {
        name: "LandingPage",
        components: {
            About,
            Chat
        }
    };
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

    .split {
        height: 100%;
        overflow-x: hidden;
        position: fixed;
    }
</style>
