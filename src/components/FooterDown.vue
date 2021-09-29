<template>
    <footer>
        <h2>FooterDown</h2>
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
@import "@/assets/style/variables.scss";
  h2{
    color: rgb(121, 0, 235);
  }
</style>