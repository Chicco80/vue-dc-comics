<template>
<div class="bck">
<ul class="footer-icons">
    <li v-for="(icon, index) in icons" :key="index"><img :src="icon.img" alt=""> {{icon.testo}}</li>
</ul>
</div>
    
</template>//:src=" 'img/avatar'+ contacts[activeContactIndex].avatar +'.jpg'"

<script>
export default {
    name:'AppFooter',
    data(){
        return{
            icons:[
                {
                    img: require('../assets/img/buy-comics-digital-comics.png'),
                    testo:'DIGITAL COMICS',
                },
                {
                    img: '../assets/img/buy-comics-mercandise-comics.png',
                    testo:'DC MERCANDISE ',
                },
                {
                    img:'../assets/img/buy-comics-shop-comics.png',
                    testo:'SUBSCRIPTION',
                },
                {
                    img:'../assets/img/buy-comics-subscriptions-comics.png',
                    testo:'COMIC SHOP LOCATO',
                },
                {
                    img:'../assets/img/buy-comics-power-comics.png',
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
</style>