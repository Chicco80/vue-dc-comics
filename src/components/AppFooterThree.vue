<template>
<div class="container-fluid">
    <div class="container">
        <button>Sing-Up Now</button>
    </div>
    <div class="social">
        <ul>
            <li class="follow">FOLLOW US</li>
            <li><a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a></li>
            <li><a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a></li>
            <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
            <li><a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a></li>
            <li><a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a></li>
        </ul>
    </div>
</div>

    
</template>

<script>
export default {
    name:'AppFooterThree',
}
</script>

<style scoped lang="scss">
@import '../style/variables';

.container-fluid{
    display: flex;
    justify-content: space-between;
    align-items: center;
      height: 100px;
    background-color: $greyFooter;
}
.container{
    padding: 20px;
}
button{
    width: 150px;
    height: 50px;
    border: 2px solid $blueFooter;
    color: white;
    font-size:20px;
    background-color: $greyFooter ;
}

ul{
    display: flex;
    list-style-type: none;
    padding: 20px;
}
li{
    padding: 20px;
}
.follow{
    font-size: 20px;
    color: $blueFooter;
    padding-top:25px
}


</style>