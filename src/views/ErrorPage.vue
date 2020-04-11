<template>
<section class="error-page">
    <h1>Oops! Something seems off!</h1>
    <a href="/" class="anchor-link">Back to home</a>
    <div class="graphics-container">
        <ErrorDisplay class="graphics"/>
    </div>
</section>
   
</template>

<script>
import ErrorDisplay from '../components/ErrorDisplay';
export default {
    name:"ErrorPage",
    components:{
        ErrorDisplay
    }
}
</script>

<style  scoped>
.error-page{
    margin-top:2rem;
    display:flex;
    flex-direction:column;
    justify-content: space-between;
    align-items: center;
}

.graphics-container{
    flex:0 0 1;
    width:40rem;
    height:30rem;
     margin-top:5rem;
}
.graphics{
   width:100%;
   height:100%;
}

.anchor-link:link,
.anchor-link:visited{
    text-transform: uppercase;
    text-decoration: none;
    color:#099456;
    font-weight:bold;
}

.anchor-link:hover,
.anchor-link:active{
    color:#01502d;
}


</style>