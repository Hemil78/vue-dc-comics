<template>
    <div class="box-jumbo">
        <div class="current-series">
            <h2>CURRENT SERIES</h2>
        </div>
    </div>
</template>

<script>
export default {
  name: "Jumbotron"
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

@import "@/assets/style/variables.scss";

.box-jumbo{
    width: 100%;
    height: 350px;
    position: relative;

    .current-series{
        display: inline-block;
        padding: 8px 30px;
        background-color: $mainColor;
        color: #fff;
        position: absolute;
        left: 25px;
        bottom: -24px;
    }
}

</style>

    
    
  
      