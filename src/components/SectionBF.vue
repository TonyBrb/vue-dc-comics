<template>
  <section class="bf-container">
    <div class="container">
      <div class="bf-box">
        <div class="bf-img">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="">
        </div>
        <span>DIGITAL COMICS</span>
      </div>
      <div class="bf-box">
        <div class="bf-img">
          <img src="../assets/img/buy-comics-merchandise.png" alt="">
        </div>
        <span>DC MERCHANDISE</span>
      </div>
      <div class="bf-box">
        <div class="bf-img">
          <img src="../assets/img/buy-comics-subscriptions.png" alt="">
        </div>
        <span>SUBSCRIPTION</span>
      </div>
      <div class="bf-box">
        <div class="bf-img">
          <img src="../assets/img/buy-comics-shop-locator.png" alt="">
        </div>
        <span>COMIC SHOP LOCATOR</span>
      </div>
      <div class="bf-box">
        <div class="bf-img">
          <img src="../assets/img/buy-dc-power-visa.svg" alt="">
        </div>
        <span>DC POWER VISA</span>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SectionBF'

}
</script>

<style lang="scss" scoped>
@import "../assets/style/mixins.scss";
  .bf-container{
    background-color: #0282F9;
    color: white;
    .bf-img{
      width: 35px;
    }

    .bf-box{
      @include center();
      span{
        padding: 10px;
        font-size: 12px;
      }
    }
  }

  .container{
    display: flex;
    justify-content: space-around;
    padding-top: 30px;
    padding: 30px;
  }


</style>