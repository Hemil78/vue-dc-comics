<template>

    <div class="icons-descript">
        <ul>

          <li v-for="(link, index) in menu" :key="index">
            <a href="#">
              <img :src= "link.src">
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
          "src": "~@/assets/images/buy-comics-digital-comics.png",
          "current": false
        },
        {
          "text": "DC MERCHANDISE",
          "src": "~@/assets/images/buy-comics-merchandise.png",
          "current": false
        },
        {
          "text": "SUBSCRIPTION",
          "src": "~@/assets/images/buy-comics-subscriptions.png",
          "current": true
        },
        {
          "text": "COMIC SHOP LOCATION",
          "src": "~@/assets/images/buy-comics-shop-locator.png",
          "current": false
        },
        {
          "text": "DC POWER VISA",
          "src": "~@/assets/images/buy-dc-power-visa.svg",
          "current": false
        }
        
      ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "@/assets/style/variables.scss";

.icons-descript{
  width: 100%;
  ul{
    display: flex;
    justify-content: space-around;
    align-items: center;
    list-style: none;
    padding: 55px 0;
    li{
      &:hover{
        background-color: rgba(255, 255, 255, 0.377);
      }
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