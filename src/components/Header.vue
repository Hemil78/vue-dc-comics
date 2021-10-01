<template>
    <header>
        <div class="logo">
          <img src="../assets/img/dc-logo.png" alt="logo dc">
        </div>
        <nav>
          <ul>
            <li v-for="(link, index) in menu" :key="index">
              <a :href="link.url" :class="{ active : link.current }">{{link.text}}</a>
            </li>

          </ul>
        </nav>
    </header>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      menu: [
        {
          text: "CHARACTERS",
          url: "#",
          current: false
        },
                {
          text: "COMICS",
          url: "#",
          current: false
        },
                {
          text: "MOVIES",
          url: "#",
          current: true
        },
                {
          text: "TV",
          url: "#",
          current: false
        },
                {
          text: "GAMES",
          url: "#",
          current: false
        },
                {
          text: "COLLECTIBLES",
          url: "#",
          current: false
        },
                {
          text: "VIDEOS",
          url: "#",
          current: false
        },
                {
          text: "FANS",
          url: "#",
          current: false
        },
                {
          text: "NEWS",
          url: "#",
          current: false
        },
                {
          text: "SHOP",
          url: "#",
          current: false
        }
      ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

@import "../assets/style/common.scss";

header{
  width: 100%;
  padding: 15px 0;
  display: flex;
  justify-content: space-between;
  align-items: center;

  img{
    width: 80px;
  }

  nav{
    ul{
    display: flex;
    list-style: none;
      li{
        margin-left: 25px;
        a{
          display: inline-block;
          text-decoration: none;
          font-weight: bold;
          color: #464646;
          &.active{
            color: #c4c4c4;
          }
        }
      }
    }
  }
}


    
    
  
      
</style>

    
  