<template>
  <div id="app">
    <app-header/>
    <main>
      <app-main/>
      <app-main-two/>
    </main> 
    <footer>
      <app-footer/>
      <app-footer-two/>
      <app-footer-three/>
    </footer>
  </div>
  
</template>

<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'
import AppFooterTwo from './components/AppFooterTwo.vue'
import AppFooterThree from './components/AppFooterThree.vue'
import AppMainTwo from './components/AppMainTwo.vue'




export default {
  name: 'App',
  components: {
    AppHeader,
    AppMain,
    AppFooter,
    AppFooterTwo,
    AppFooterThree,
    AppMainTwo,
  }
}
</script>

<style lang="scss">
@import './style/variables';
@import './style/general';


</style>
