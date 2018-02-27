<template>
  <div class="wrapper">
    <div class="box1">
      <text>12</text>
    </div>
    <div class="box2">
      <text>34</text>
    </div>
    <a href="../dist/app.weex.js">
      <text>222</text>
    </a>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App',
  data () {
    return {
    }
  }
}
</script>

<style scoped>
  .wrapper {
    justify-content: center;
    align-items: center;
  }
  .box1{
    height: 200px;
    width: 200px;
    background-image: linear-gradient(to top,black,white);
    border-width: 10px;
    border-color: #00B4FF;
    border-style: solid;
    position: relative;
    z-index: 20;
  }
  .box2{
    height: 200px;
    width: 200px;
    background-color: blue;
    position: relative;
    z-index: 30;
    bottom: 100px;
  }
</style>
