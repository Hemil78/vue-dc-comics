<template>
    <footer>
        <div class="btn-footer">
          <button>SIGN-UP NOW!</button>
        </div>
        <div class="icons-footer">

          <span>FOLLOW US</span>

          <ul>
            <li>
              <a href="#">
                <img src="../assets/img/footer-facebook.png" alt="logo facebbok">
              </a>
            </li>
            <li>
              <a href="#">
                <img src="../assets/img/footer-twitter.png" alt="logo twitter">
              </a>
            </li>
            <li>
              <a href="#">
                <img src="../assets/img/footer-youtube.png" alt="logo youtube">
              </a>
            </li>
            <li>
              <a href="#">
                <img src="../assets/img/footer-pinterest.png" alt="logo pinterest">
              </a>
            </li>
            <li>
              <a href="#">
                <img src="../assets/img/footer-periscope.png" alt="logo periscope">
              </a>
            </li>
          </ul>
        </div>
    </footer>
</template>

<script>
export default {
  name: "FooterDown",
  props: {
    msg: String
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

@import "../assets/style/common.scss";

footer{
  display: flex;
  justify-content: space-between;
  padding: 20px 0;

  .btn-footer{

    button{
      background-color: transparent;
      border: none;
      border: 1px solid $mainColor;
      color: #fff;
      padding: 10px;
      cursor: pointer;

      &:hover{
        background-color: $mainColor;
      }
    }
  }

  .icons-footer{
  display: flex;
  align-items: center;

    span{
      color: $mainColor;
      font-size: 18px;
      font-weight: bold;
    }
    ul{
      display: flex;
      list-style: none;
      margin-left: 10px;

      li{
        margin-left: 15px;
      }
    }
  }
}

          
</style>