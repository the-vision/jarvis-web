<template>
  <div class="main">
    <div class="split left">
      <section class="about-section">
        <div class="secondary-heading">
            <h2>Meet The Vision</h2>
        </div>
        <div class="about-info">
          <p class="paragraph">
            Vision is the evolution of <a class="anchors" href="https://chatwithjarvis.com/history.html">Jarvis</a>. It aims to write generic modules which can be exposed as standalone APIs as well as plugged into various platforms like Messenger, Slack, Discord, Telegram, Skype, etc.
          </p>
          <p class="paragraph">
            For a quick overview of how AI is used in this project, see <a class="anchors" href="https://vimeo.com/238717639">https://vimeo.com/238717639.</a> 
          </p>
        </div>
        <div class="secondary-heading">
          <h2>What?</h2>
        </div>
        <div class="about-info">
          <p class="paragraph">
            J.A.R.V.I.S. is a community-driven python bot that aims to be as simple as possible to serve humans with their everyday tasks.
          </p>
        </div>
         <div class="secondary-heading">
          <h2>Why?</h2>
        </div>
        <div class="about-info">
          <p class="paragraph">
            I created JARVIS with two goals in mind:
          </p>
          <ol class="list">
            <li class="list-item">
              It should have a lot of useful features (both fun and commonly used).
            </li>
             <li class="list-item">
              Anyone can contribute to this project. (As this is module-based, anybody with a decent knowledge of Python can contribute.) One of the prime goals of this project is to lower the entry barrier into the world of open source.
            </li>
          </ol>
        </div>
        <div class="secondary-heading">
          <h2>Vision's Vision</h2>
        </div>
        <div class="about-info">
          <ol class="list">
            <li class="list-item">
              Get <a class="anchors" href="https://chatwithjarvis.com/progress.html">100</a>  people started with open-source in 2019!
            </li>
            <li class="list-item">
              Build a community to scale this.
            </li>
          </ol>
          <p class="paragraph">
            If you're willing to help even one person in his / her first Pull Request, reach out to me via <a class="anchors" href="https://twitter.com/SwapAgarwal">Twitter.</a>  All the help is appreciated! 🙌
          </p>
        </div>
      </section>
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
  height:100%;
  overflow-x:hidden;
  position: fixed;
}
.left {
  left: 0;
  background-color: #fafafa;
  width: 70%;
}
.right {
  right: 0;
  background-color: #ececec;
  width: 30%;
  float: right;
}
.about-section{
  width:90%;
  margin:3rem auto;
  padding-bottom:4rem;
 }
.secondary-heading{
  font-size:1.5rem;
  margin:1rem auto;
  text-align:center;
}
.about-info{
  padding:0 2rem;  
}
.paragraph{
  text-align:justify;
  text-justify: inter-word;
  font-size:1.2rem;
  margin:1rem 0;
  color:#2c3e50;
 }

.list{
  margin:0;
  padding-left:1rem;
}
.list-item{
  text-align:left;
  margin:1rem;
  font-size:1.1rem;
}

.anchors:link,
.anchors:visited{
  text-decoration:none;
  color:#3eaf7c;
}
.anchors:hover,
.anchors:active{
  color:#099456;
  text-decoration: underline;
}

</style>
