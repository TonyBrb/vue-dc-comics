<template>
  <div>
    <Header :menu="links" />
    <Main />
    <SectionBF />
    <Footer />
  </div>
</template>

<script>

import Header from "./components/Header.vue"
import Main from "./components/Main.vue"
import SectionBF from "./components/SectionBF.vue"
import Footer from "./components/Footer.vue"

export default {
  name: 'App',
  data(){
    return{
      links:[
        {
          url:'#',
          text: 'CHARACTERS',
          current: false
        },
        {
          url:'#',
          text: 'COMICS',
          current: true
        },
        {
          url:'#',
          text: 'MOVIES',
          current: false
        },
        {
          url:'#',
          text: 'TV',
          current: false
        },
        {
          url:'#',
          text: 'GAMES',
          current: false
        },
        {
          url:'#',
          text: 'COLLECTIBLES',
          current: false
        },
        {
          url:'#',
          text: 'VIDEOS',
          current: false
        },
        {
          url:'#',
          text: 'FANS',
          current: false
        },
        {
          url:'#',
          text: 'NEWS',
          current: false
        },
        {
          url:'#',
          text: 'SHOP',
          current: false
        }
      ]
    }
  },

  components: {
    Header,
    Main,
    SectionBF,
    Footer
  }
}
</script>

<style lang="scss">
  @import "./assets/style/general.scss";
  @import "./assets/style/utilities.scss";
  

</style>
