<template>
  <div class="productCard">
    <img :src="cardImage" :alt="cardTitle">
    <h6>{{cardTitle}}</h6>
  </div>
</template>

<script>
export default {
  name: 'Card',
  props:{
    cardImage: String,
    cardTitle: String
  }
}
</script>

<style lang="scss" scoped>
  .productCard{
    flex-basis: 16.6%;
    height: 160px;
    border: solid 10px #1C1C1C;
    margin-top: 40px;
    margin-bottom: 40px;
    
    img{
      width: 100%;
      height: 100%;
      object-fit: cover;
      object-position: 100% 0;
    }

    h6{
      font-weight: lighter;
      padding-top: 10px;
      text-transform: uppercase;
    }
  }
</style>