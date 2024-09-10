<script>

</script>

<template>
  <footer>
    <div class="footer-icons">

      <div class="icon">
        <img src="../../img/buy-comics-digital-comics.png">
        <a href="#">Digital Comics</a>
      </div>
      <div class="icon">
        <img src="../../img/buy-comics-merchandise.png">
        <a href="#">DC Merchandise</a>
      </div>
      <div class="icon">
        <img src="../../img/buy-comics-subscriptions.png" alt="">
        <a href="#">Subscription</a>
      </div>
      <div class="icon">
        <img src="../../img/buy-comics-shop-locator.png" alt="">
        <a href="#">Comic Shop Locator</a>
      </div>
      <div class="icon">
        <img src="../../img/buy-dc-power-visa.svg" alt="">
        <a href="#">DC Power Visa</a>
      </div>
    </div>
    <div class="footer-info">
      <div class="column">
        <h4>DC Comics</h4>
        <ul>
          <li><a href="#">Characters</a></li>
          <li><a href="#">Comics</a></li>
          <li><a href="#">Movies</a></li>
          <li><a href="#">TV</a></li>
          <li><a href="#">Games</a></li>
          <li><a href="#">Videos</a></li>
          <li><a href="#">News</a></li>
        </ul>
        <h4>shop</h4>
        <ul>
          <li><a href="#">Characters</a></li>
          <li><a href="#">Comics</a></li>
          <li><a href="#">Movies</a></li>
        </ul>
      </div>
      <div class="column">
        <h4>DC</h4>
        <ul>
          <li><a href="#">Terms of Use</a></li>
          <li><a href="#">Privacy Policy</a></li>
          <li><a href="#">Ad Choices</a></li>
          <li><a href="#">Movies</a></li>
          <li><a href="#">TV</a></li>
          <li><a href="#">Games</a></li>
          <li><a href="#">Videos</a></li>
          <li><a href="#">News</a></li>
        </ul>
      </div>
      <div class="column">
        <h4>Sites</h4>
        <ul>
          <li><a href="#">MAD Magazine</a></li>
          <li><a href="#">DC Kids</a></li>
          <li><a href="#">DC Universe</a></li>
          <li><a href="#">DC PowerVisa</a></li>
        </ul>
      </div>
      <img src="../../img/dc-logo-bg.png">
    </div>
    <div class="last-row">
      <div class="register">
        <button>
          SIGN UP NOW
        </button>
        <div class="follow-us">
          <h5>FOLLOW US</h5>
          <div class="social-icons">
            <a href="#" ><img src="../../img/footer-facebook.png" alt="Facebook"></a>
            <a href="#" ><img src="../../img/footer-twitter.png" alt="Twitter"></a>
            <a href="#" ><img src="../../img/footer-youtube.png" alt="YouTube"></a>
            <a href="#" ><img src="../../img/footer-pinterest.png" alt="Pinterest"></a>
          </div>
        </div>
      </div>
      
    </div>
  </footer>
</template>

<style lang="scss" scoped>
footer {
  background-color: #000;
  color: #fff;
  background-image: url(../../img/footer-bg.jpg);

  .footer-icons {
    display: flex;
    justify-content: center;
    background-color: #0074e8;
    padding: 20px 0;

    .icon {
      display: flex;
      margin: 0 80px;
      width: 100px;
      a {
        color: #fff;
        text-decoration: none;
        font-weight: bold;
        display: inline-block;
        text-align: center;
        padding: 20px;
      }
    }
  }

  .footer-info {
    width: 1200px;
    margin: auto;
    display: flex;
    padding: 20px;

    .column {
      padding: 20px;
      h4 {
        margin-bottom: 10px;
        color:white;
      }

      ul {
        list-style-type: none;

        li {
          margin-bottom: 5px;

          a {
            color: #fff;
            text-decoration: none;
            font-size: 14px;

            &:hover {
              text-decoration: underline;
            }
          }
        }
      }
      img{
        width: 100%;
        height: 100%;
        object-fit: cover;
      }
    }
  }
  .last-row{
    background-color: black;
  .register{
    padding: 20px;
    display: flex;
    width: 1000px;
    margin: auto;
    justify-content: space-between;


    button{
      
      background-color: black ;
      color: white;
      padding: 10px;
      border: 2px solid blue;
    }
  }
}
}
</style>
npm,