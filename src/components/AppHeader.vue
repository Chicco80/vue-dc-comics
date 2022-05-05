<template>
<header>
  <div class="logo"><img src="../assets/img/dc-logo.png" alt="logo"></div>
    <nav>
      <ul>
        <li v-for="(item, index) in links" :key="index" :class="{'selected' : item.active}">{{item.testo}}</li>
      </ul>
    </nav>
</header>
  
</template>

<script>
export default {
  name: 'AppHeader',
  data(){
    return{
      links:[
        {
          testo:'CHARACTERS',
          link:'',
          active:'false',
        },
        {
          testo:'COMICS',
          link:'',
          active:'true',
        },
        {
          testo:'MOVIES',
          link:'',
          active:'false',
        },
        {
          testo:'TV',
          link:'',
          active:'false',
        },
        {
          testo:'GAMES',
          link:'',
          active:'false',
        },
        {
          testo:'COLLECTIBLES',
          link:'',
          active:'false',
        },
        {
          testo:'VIDEO',
          link:'',
          active:'false',
        },
        {
          testo:'FANS',
          link:'',
          active:'false',
        },
        {
          testo:'NEWS',
          link:'',
          active:'false',
        },
        {
          testo:'SHOP',
          link:'',
          active:'false',
        },
      ],
    }
  }
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import '../style/variables';

header{
  margin: 0 auto;
  display: flex;
  justify-content: space-around;
  align-items: center;
  height: 110px;
  font-size: 12px;
  font-weight: bold;

}

  ul{
    display: flex;
  }
  li{
    padding: 10px;
    list-style-type: none;
    
  }
  .selected{
    border-bottom: 2px solid $blueFooter;
  }
</style>
