<template>
  <div class="container">
    <div class="logo">
      <img src="../assets/dc-logo.png" alt="logo DC">
    </div>
    <div class="menu">
      <ul>
        <li><a href="#">CHARACTERS</a></li>
        <li><a href="#">COMICS</a></li>
        <li><a href="#">MOVIES</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">GAMES</a></li>
        <li><a href="#">COLLECTIBLES</a></li>
        <li><a href="#">VIDEOS</a></li>
        <li><a href="#">FANS</a></li>
        <li><a href="#">NEWS</a></li>
        <li><a href="#">SHOP</a></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style lang="scss" scoped>
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
    ul{
      display: flex;
      list-style: none;
        li{
          padding: 5px;
          font-size: 12px;
          color: black;
          a{
            text-decoration: none;
            color: black;
          }
        }
    }
  }

</style>