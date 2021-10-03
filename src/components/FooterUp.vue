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
              <li v-for="(link, index) in menu" :key="index"><a href="#">{{link.text}}</a></li>
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
  },
    data() {
    return {
      menu: [
        {
          text: "Terms Of Use",
          url: "#",
          current: false
        },
        {
          text: "Privacy policy(New)",
          url: "#",
          current: false
        },
        {
          text: "Ad Choices",
          url: "#",
          current: true
        },
        {
          text: "Advertising",
          url: "#",
          current: false
        },
        {
          text: "Jobs",
          url: "#",
          current: false
        },
        {
          text: "Subscriptions",
          url: "#",
          current: false
        },
        {
          text: "Talent Workshops",
          url: "#",
          current: false
        },
        {
          text: "CPSC Certificates",
          url: "#",
          current: false
        },
        {
          text: "Ratings",
          url: "#",
          current: false
        },
        {
          text: "Shop Help",
          url: "#",
          current: false
        },
        {
          text: "Contact Us",
          url: "#",
          current: false
        }
      ]
    }
  },
  
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
  margin-right: 70px;
}


</style>