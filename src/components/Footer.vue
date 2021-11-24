<template>
  <div class="footer-container-up">
    <div class="container">
      <div class="left-block">
        <div class="left-links">
          <h4>DC COMICS</h4>
          <ul>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">Tv</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
          <h4>SHOP</h4>
          <ul>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
          </ul>
        </div>

          <div class="centre-links">
          <h4>DC</h4>
          <ul>
            <li><a href="#">Terms of use</a></li>
            <li><a href="#">Privacy policy (new)</a></li>
            <li><a href="#">Ad Choices</a></li>
            <li><a href="#">Adversiting</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">Subscriptions</a></li>
            <li><a href="#">Talent Workshops</a></li>
            <li><a href="#">CPSC Certificates</a></li>
            <li><a href="#">Rating</a></li>
            <li><a href="#">Shop Help</a></li>
            <li><a href="#">Concact Us</a></li>
          </ul>
        </div>

          <div class="right-links">
          <h4>SITES</h4>
          <ul>
            <li><a href="#">DC</a></li>
            <li><a href="#">MAD Magazine</a></li>
            <li><a href="#">DC Kids</a></li>
            <li><a href="#">DC Universe</a></li>
            <li><a href="#">DC Power Visa</a></li>
          </ul>
        </div>
      </div>
      <div class="right-block">
        <img src="../assets/img/dc-logo-bg.png" alt="">
      </div>
    </div>
    <div class="footer-container-down">
      <div class="container">
        <button class="btn">SIGN-UP NOW!</button>
        <div class="right-container-down">
          <h4>FOLLOW US</h4>
          <div class="social">
            <img src="../assets/img/footer-facebook.png" alt="">
          </div>
          <div class="social">
            <img src="../assets/img/footer-twitter.png" alt="">
          </div>
          <div class="social">
            <img src="../assets/img/footer-youtube.png" alt="">
          </div>
          <div class="social">
            <img src="../assets/img/footer-pinterest.png" alt="">
          </div>
          <div class="social">
            <img src="../assets/img/footer-periscope.png" alt="">
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style lang="scss" scoped>
  .footer-container-up{
    width: 100%;
    background-image: url("../assets/img/footer-bg.jpg");
      .container{
      display: flex;
      justify-content: space-between;
    }

    .left-block{
      display: flex;
      justify-content: space-between;
      align-items: center;
      h4{
        color: white;
        padding-top: 10px;
        padding-bottom: 20px;
      }
      ul{
        list-style: none;
        li{
          font-size: 12px;
          color: #616A6C;
          a{
            text-decoration: none;
            color: #616A6C;
          }
        }
      }

      .centre-links{
        margin-top: -15px;
      }
      .right-links{
        margin-top: -115px;
      }
    }

    .left-block, .right-block{
      width: 40%;
    }

  }

  .footer-container-down{
    width: 100%;
    background-color: #303030;
    padding: 50px;

    .btn{
      padding: 10px;
      background-color: #303030;
      color: white;
      font-weight: bold;
      border: 2px solid #0282F9;
    }

    h4{
      color: #0282F9;
    }

    .social{
      width: 25px;
    }

    .right-container-down{
      width: 285px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
  }
</style>