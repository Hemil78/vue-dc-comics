<template>

    <div class="icons-descript">
        <ul>

          <li v-for="(link, index) in menu" :key="index">
            <a href="#">
              <img :src= "link.img">
              <span>{{link.text}}</span>
            </a>
          </li>

        </ul>
    </div>

</template>

<script>
export default {
  name: "Digital",
  data() {
    return {
      menu: [
        {
          "text": "DIGITAL COMICS",
          "img": require("../assets/img/buy-comics-digital-comics.png"),
          "current": false
        },
        {
          "text": "DC MERCHANDISE",
          "img": require("../assets/img/buy-comics-merchandise.png"),
          "current": false
        },
        {
          "text": "SUBSCRIPTION",
          "img": require("../assets/img/buy-comics-subscriptions.png"),
          "current": true
        },
        {
          "text": "COMIC SHOP LOCATION",
          "img": require("../assets/img/buy-comics-shop-locator.png"),
          "current": false
        },
        {
          "text": "DC POWER VISA",
          "img": require("../assets/img/buy-dc-power-visa.svg"),
          "current": false
        }
        
      ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/style/common.scss";

.icons-descript{
  width: 100%;
  ul{
    display: flex;
    justify-content: space-around;
    align-items: center;
    list-style: none;
    padding: 55px 0;
    li{
      
      a{
        display: inline-block;
        text-decoration: none;
        color: #fff;
        img{
          width: 50px;
          vertical-align: middle;
          margin-right: 15px;
        }
      }
    }
  }
}
</style>