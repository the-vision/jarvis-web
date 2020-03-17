
<template>

    <section style="background: rgb(123,198,255);background: linear-gradient(0deg, rgba(123,198,255,1) 0%, rgba(107,175,229,1) 100%);height: 1066px;width: 1936px;">
        <div class="row" style="height: 208px; background: rgb(32,68,96); background: linear-gradient(0deg, rgba(32,68,96,1) 0%, rgba(45,97,136,1) 14%, rgba(64,136,191,1) 100%);">
            <div class="col justify-content-center align-items-center align-content-center align-self-center">
                <h1 class="text-light d-xl-flex justify-content-xl-center" style="font-family: 'Roboto Condensed', sans-serif;"><strong>15Feb,2020</strong></h1>
                <h1 class="text-light d-xl-flex justify-content-xl-center" style="font-family: 'Roboto Condensed', sans-serif;"><strong>10:40:53</strong></h1>
            </div>
            <div class="col d-flex flex-shrink-0 justify-content-center align-items-center align-content-center flex-wrap justify-content-xl-center"><img class="d-flex align-self-center img-fluid" src="../assets/img/6951267.png" height="208px" width="208px"></div>
            <div class="col" style="height: 208px;"><img class="rounded" src="../assets/img/Download-Message-Png-Image-65379-For-Designing-Projects.png" width="100px" style="margin: 51px 205px 0px 254px;"></div>
        </div>
        <div class="row">
            <div class="col">
                <p style="margin: 30px;background-color:#87DBF1">Paragraph</p>
                <p style="margin: 30px;background-color:#87DBF1">Paragraph</p>
                <p style="        margin: 30px;
        background-color: #87DBF1
">Paragraph</p>
                <p style="margin: 30px;background-color:#87DBF1">Paragraph</p>
                <p style="margin: 30px;background-color:#87DBF1">Paragraph</p>
                <p style="margin: 30px;background-color:#87DBF1">Paragraph</p>
                <p style="margin: 30px;background-color:#87DBF1">Paragraph</p>
                <p style="margin: 30px;background-color:#87DBF1">Paragraph</p>
                <p style="margin: 30px;background-color:#87DBF1">Paragraph</p>
                <p style="margin: 30px;background-color:#87DBF1">Paragraph</p>
            </div>
            <div class="col">
                <p style="margin: 60px 30px 30px 30px;background-color:#C0D9EB">Paragraph</p>
                <p style="margin:30px;background-color:#C0D9EB">Paragraph</p>
                <p style="margin:30px;background-color:#C0D9EB">Paragraph</p>
                <p style="margin:30px;background-color:#C0D9EB">Paragraph</p>
                <p style="margin:30px;background-color:#C0D9EB">Paragraph</p>
                <p style="margin:30px;background-color:#C0D9EB">Paragraph</p>
                <p style="margin:30px;background-color:#C0D9EB">Paragraph</p>
                <p style="margin:30px;background-color:#C0D9EB">Paragraph</p>
                <p style="margin:30px;background-color:#C0D9EB">Paragraph</p>
                <p style="margin:30px;background-color:#C0D9EB">Paragraph</p>
            </div>
        </div>
        <div class="row" style="height: 98px;">
            <div class="col d-flex justify-content-center align-items-center align-content-center" style="height: 168px;"><input type="text" style="height: 97px;width: 1253px;color:"><img src="../assets/img/6951267.png" style="height: 100px;"></div>
        </div>
    </section>

</template>

<script>
    export default {
        name: "LandingPage"
    };
=======
  <div class="main">
    <About class="split"/>
    <Chat  class="split"/>
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
=======
.split {
  height: 100%;
  overflow-x: hidden;
  position: fixed;
}

</style>
