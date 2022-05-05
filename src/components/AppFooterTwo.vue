<template>
<div class="center">
    <div class="row">
        <div class="col">
            <ul>
                <li><a class="big" href="#">DC COMICS</a></li>
                <li><a href="#"> Character</a></li>
                <li><a href="#"> Movies</a></li>
                <li><a href="#"> TV</a></li>
                <li><a href="#"> Games</a></li>
                <li><a href="#"> Videos</a></li>
                <li><a href="#"> News</a></li>
                <div class="bigTwo">
                    <ul>
                        <li><a class="big" href="#">SHOP</a></li>
                        <li><a href="#">Shop DC</a></li>
                        <li><a href="#">Shop DC Colletibles</a></li>
                    </ul>
                </div>
            </ul>
        </div>
        <div class="col">
            <ul>
                <li><a class="big" href="#">DC</a></li>
                <li><a href="#">Tearms Of Use</a></li>
                <li><a href="#">Privacy policy (New)</a></li>
                <li><a href="#">Ad Choices</a></li>
                <li><a href="#">Advertising</a></li>
                <li><a href="#">Jobs</a></li>
                <li><a href="#">subscriptions</a></li>
                <li><a href="#">Talent Workshops</a></li>
                <li><a href="#">CPSC Certificates</a></li>
                <li><a href="#">Ratings</a></li>
                <li><a href="#">Shop Helps</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
        </div>
        <div class="col">
                <ul>
                <li><a class="big" href="#">SITES</a></li>
                <li><a href="#">DC</a></li>
                <li><a href="#">DC Kids</a></li>
                <li><a href="#">DC Universe</a></li>
                <li><a href="#">DC Power Visa</a></li>
            </ul>
        </div>
          <div class="col logo ">
            <img class="logo-footer" src="../assets/img/dc-logo.png" alt="">
        </div>
    </div>
      
</div>
</template>

<script>
export default {
    name:'AppFooterTwo',
}
</script>

<style scoped lang="scss">
@import '../style/variables';
.center{
    margin:0 auto;
    width: 100%;
    height: 350px;
    background-image: url("../assets/img/footer-bg.jpg");
    background-repeat: no-repeat;
    background-size:cover ;
    padding-top: 50px;
    position: relative;
    overflow: hidden;
}


 .logo-footer{
    position: absolute;
    top:-30px;
    right:350px;
    width: 450px;
    height: 450px;
    transform: rotate(-30deg);
    overflow: hidden;
}
li{
    list-style-type: none;
}

a{
    color:grey;
    text-decoration: none;

}
.big{
    font-size: 20px;
    font-weight: bold;
    margin: 20px 0;
    color:white;
}
.bigTwo{
    padding: 10px 0;
    

}
.row{
    display: flex;
    width: 80%;
    margin: 0 auto;
    
}
.col{
    padding:20px;
}

</style>