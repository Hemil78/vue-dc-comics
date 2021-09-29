<template>

    <div class="icons-descript">
        <ul>
          <li>
            <a href="#">
              <img src="@/assets/images/buy-comics-digital-comics.png" alt="">
              <span>DIGITAL COMICS</span>
            </a>
          </li>

          <li>
            <a href="#">
              <img src="@/assets/images/buy-comics-merchandise.png" alt="">
              <span>DIGITAL COMICS</span>
            </a>
          </li>

          <li>
            <a href="#">
              <img src="@/assets/images/buy-comics-subscriptions.png" alt="">
              <span>DIGITAL COMICS</span>
            </a>
          </li>

          <li>
            <a href="#">
              <img src="@/assets/images/buy-comics-shop-locator.png" alt="">
              <span>DIGITAL COMICS</span>
            </a>
          </li>

          <li>
            <a href="#">
              <img src="@/assets/images/buy-dc-power-visa.svg" alt="">
              <span>DIGITAL COMICS</span>
            </a>
          </li>

        </ul>
    </div>

</template>

<script>
export default {
  name: "Digital",
  props: {
    msg: String
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