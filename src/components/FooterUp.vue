<template>
    <footer>
        <h2>FooterUp</h2>
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
@import "@/assets/style/variables.scss";
  h2{
    color: rgb(235, 0, 204);
  }

</style>