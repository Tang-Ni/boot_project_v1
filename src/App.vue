<template>
  <div id="app"> 
    <!-- <img src="./assets/logo.png"> -->
    <router-view></router-view>
  </div>
</template>

<script>
  export default {
    name: 'app'
  }
</script>

<style lang="scss">
  // 引入css库
  @import "../node_modules/font-awesome/css/font-awesome.min.css";
  @import "../node_modules/normalize.css"; 
  // 引入scss文件
  @import "scss/_container";
  @import "scss/_clearfix";

  html,body {
    height: 100%;
    overflow: hidden;
  }

  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale; 
    background: #435571;
    min-height: 100%; 
    .loading-container{
      text-align: center;
    }
  }
  
  .text-white{
    color: #fff;
  }
</style>
