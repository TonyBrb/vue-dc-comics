<template>
  <div>
    <Header />
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
