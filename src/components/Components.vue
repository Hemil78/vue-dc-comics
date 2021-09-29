<template>
    <div>
        <h2>Components</h2>
    </div>
</template>

<script>
export default {
  name: "Components",
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  h2{
    color: green;
  }
</style>