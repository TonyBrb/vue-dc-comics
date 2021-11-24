<template>
  <div class="container">
    <div class="logo">
      <img src="../assets/img/dc-logo.png" alt="logo DC">
    </div>
    <div class="menu">
      <ul>
        <li v-for="(link,index) in links" :key="index">
          <a :class="{active: item.current}" :href="link.url">{{link.text}}</a>
          </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
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
  }
}
</script>

<style lang="scss" scoped>
@import "../assets/style/mixins.scss";
  .container{
    display: flex;
    justify-content: space-between;
  }

  .logo{
    width: 60px;
    img{
      width: 100%;
    }
    
  }

  .menu{
    @include center();
    ul{
      display: flex;
      list-style: none;
        li{
          line-height: 51px;
          padding: 5px;
          font-size: 12px;
          color: black;
            &:hover,
            &.active{
              border-bottom: solid 3px #0282F9;
            }
          a{
            text-decoration: none;
            color: black;
           
          }
        }
    }
  }

</style>