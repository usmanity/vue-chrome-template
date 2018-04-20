<template>
  <div class="hello">
    <h1>
      <img src="../assets/bee.png" class="bee">
      {{ msg }}
    </h1>
  </div>
</template>

<script>
export default {
  name: 'Hello',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
h3 {
  margin: 40px 0 0;
}
.bee {
  width: 30px;
  height: 30px;
}
</style>
