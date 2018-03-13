<template>
  <div id="app">
    <img src="./icons/bee.png" class="bee-image">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
import config from './config';
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to your chrome extension',
      image_base: config.IMAGE_BASE,
    }
  },
}
</script>

<style lang="scss">
body {
  width: 300px;
  height: 300px;
}
#app {
  color: #2c3e50;
  margin-top: 60px;
}
.bee-image {
  width: 128px;
}
</style>

