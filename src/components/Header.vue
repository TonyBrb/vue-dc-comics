<template>
  <div class="container">
    <div class="logo">
      <img src="../assets/img/dc-logo.png" alt="logo DC">
    </div>
    <div class="menu">
      <ul>
        <li v-for="(link,index) in menu" :key="index">
          <a :href="link.url">{{link.text}}</a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  props: ['menu']
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
            &:hover{
              border-bottom: solid 3px #0282F9;
            }

          a{
            
            text-decoration: none;
            color: black;
           &.active{
             border-bottom: solid 3px #0282F9;
           }
          }
        }
    }
  }

</style>