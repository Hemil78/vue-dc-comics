<template>
    <footer class="up">

        <div class="link-footerUp">

          <div class="link-left">
            <h3>DC COMICS</h3>
            <ul>
              <li><a href="#">Characters</a></li>
              <li><a href="#">Comics</a></li>
              <li><a href="#">Movies</a></li>
              <li><a href="#">TV</a></li>
              <li><a href="#">Games</a></li>
              <li><a href="#">Videos</a></li>
              <li><a href="#">News</a></li>
            </ul>

            <h3>SHOP</h3>
            <ul>
              <li><a href="#">Shop DC</a></li>
              <li><a href="#">Shop DC Collectibles</a></li>
            </ul>
          </div>
          <div class="link-central">
            <h3>DC</h3>
            <ul>
              <li><a href="#">Terms Of Use</a></li>
              <li><a href="#">Privacy policy(New)</a></li>
              <li><a href="#">Ad Choices</a></li>
              <li><a href="#">Advertising</a></li>
              <li><a href="#">Jobs</a></li>
              <li><a href="#">Subscriptions</a></li>
              <li><a href="#">Talent Workshops</a></li>
              <li><a href="#">CPSC Certificates</a></li>
              <li><a href="#">Ratings</a></li>
              <li><a href="#">Shop Help</a></li>
              <li><a href="#">Contact Us</a></li>
            </ul>
          </div>
          <div class="link-right">
                        <h3>DC COMICS</h3>
            <ul>
              <li><a href="#">DC</a></li>
              <li><a href="#">MAD Magazine</a></li>
              <li><a href="#">DC Kids</a></li>
              <li><a href="#">DC Universe</a></li>
              <li><a href="#">DC Power Visa</a></li>
            </ul>
          </div>
        </div>
        <div class="img-footerUp">
          <img src="../assets/img/dc-logo-bg.png" alt="logo dc">
        </div>
    </footer>
</template>

<script>

export default {
  name: "FooterUp",
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/style/common.scss";
  
.up{
  width: 100%;
  height: 350px;
  display: flex;
  justify-content: space-between;

  .link-footerUp{
    display: flex;
    padding: 30px 0;

    .link-left{

    }

  }
  .img-footerUp{
    overflow: hidden;

    img{
      position: relative;
      top: -43px;
      right: 0;
      width: 430px;
    }
  }
  h3{
    color: #fff;
    margin-bottom: 10px;
  }
  ul{
    list-style: none;
    margin-bottom: 25px;
  }
  li{
      
  }
  a{
    text-decoration: none;
    color: $colorIcons;
    font-size: 13px;
    &:hover{
      color: #bebebe;
    }
  }
}

.link-footerUp,
.img-footerUp{
  widows: 50%;
}

.link-left,
.link-central{
  margin-right: 30px;
}


</style>