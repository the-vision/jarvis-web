<template>
 <footer>
     <div class="footer">
        <div>
           <ul class="footer__links">
                <h4 class="footer__head">Information</h4>
                <li class="footer__links-item">
                    <a class="footer__link" href="#!">Home</a>
                </li>
                <li class="footer__links-item">
                    <a class="footer__link" href="#!">About</a>
                </li>
                <li class="footer__links-item">
                    <a class="footer__link" href="#!">History</a>
                </li>
                <li class="footer__links-item">
                    <a class="footer__link" href="#!">License</a>
                </li>
            </ul>
        </div>
        <div >
            <ul class="footer__links">
                <h4 class="footer__head">Jarvis Products</h4>
                <li class="footer__links-item">
                    <a class="footer__link" href="#!">Core</a>
                </li>
                <li class="footer__links-item">
                    <a class="footer__link" href="#!">Telegram</a>
                </li>
                <li class="footer__links-item">
                    <a class="footer__link" href="#!">Discord</a>
                </li>
                <li class="footer__links-item">
                    <a class="footer__link" href="#!">Slack</a>
                </li>
            </ul>
        </div>
        
     </div>
     <p class="copyright-text">Copyright &copy; 2020 Jarvis Web</p>
 </footer>
</template>



<script>
export default {
  name: "Footer"
};
</script>


<style scoped>

footer{
    background-color: #333;
    color:white;
    min-height:10vh;
}
.footer{
    padding-top:10px;
    max-width:1140px;
    margin:0 auto;
    display:flex;
    justify-content: space-around;
    align-items: center;
  
}

.footer__head{
   padding-top:1rem;
   letter-spacing: 2px;
   
}

.footer__links{
    list-style: none;
    display:flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
.footer__links-item{
    margin:0;
    padding:.4rem;
    align-self: flex-start;
}

.footer__link:link,.footer__link:visited{
    color:white;
    text-decoration: none;
    letter-spacing:2px;
    font-size:1rem;
}
.footer__link:active,.footer__link:hover{
    color:#05728f;
}
.copyright-text{
    padding:10px;
    font-size:14px;
}


</style>
