<template>
<div class="bck">
    <ul class="footer-icons">
        <li v-for="(icon, index) in icons" :key="index"><img :src="icon.img" alt=""> {{icon.testo}}</li>
    </ul>
</div>
    
</template>

<script>
export default {
    name:'AppFooter',
    data(){
        return{
            icons:[
                {
                    img:'./img/buy-comics-digital-comics.png',
                    testo:'DIGITAL COMICS',
                },
                {
                    img: './img/buy-comics-merchandise.png',
                    testo:'DC MERCANDISE ',
                },
                {
                    img:'./img/buy-comics-shop-locator.png',
                    testo:'SUBSCRIPTION',
                },
                {
                    img:'./img/buy-comics-subscriptions.png',
                    testo:'COMIC SHOP LOCATO',
                },
                {
                    img:'./img/buy-dc-power-visa.svg',
                    testo:'DC POWER VISA',
                },
            ],
           
        }
    }
}
</script>

<style scoped lang="scss">
@import '../style/variables';

.footer-icons{
    width: 80%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    height:200px;
    list-style-type: none;
    color:white
}
.bck{
    display: flex;
    justify-content: center;
     background-color: $blueFooter;
}
img{
    width: 50px;
    height: 50px;
}
</style>