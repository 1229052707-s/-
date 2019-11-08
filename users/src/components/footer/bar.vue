<template>
  <div class="bar" >

      <router-link to="/homepage"><span class="a"></span><p style="margin-left: 0.2rem;">首页</p></router-link>
      <router-link to="/classify"><span class="b"></span><p style="margin-left: 0.11rem;">分类</p></router-link>
      <router-link to="/shoppingCar"><span class="c"></span><p style="margin-left: 0.2rem;">购物车</p></router-link>
      <router-link to="/personalCenter"> <span class="d"></span><p>个人中心</p></router-link>


  </div>
</template>

<script>
    export default {
        name: "vfooter"
    }
</script>

<style scoped>
  .bar {
      width: 100%;
      position: fixed;
      display: flex;
      flex-direction: row;
      bottom: 0;
    background-color:white;
    }
  a{
    flex: 1;
    text-align: center;
  }
  span{
    height: 0.4rem;
    display: inline-block;
    margin-left: 15px;
    width: 55%;
  }
  p{
    color: black;
    /*margin-left: 15px;*/
  }
  .a{
    background-image: url("../../assets/vns_icon_sprites_01.png");
    background-position: 609px 43px;
    background-size: 2rem;
  }
  .b{
    background-image: url("../../assets/vns_icon_sprites_01.png");
    background-position: 562px 43px;
    background-size: 2rem;
  }
  .c{
    background-image: url("../../assets/vns_icon_sprites_01.png");
    background-position: 517px 45px;
    background-size: 2rem;
  }
  .d{
    background-image: url("../../assets/vns_icon_sprites_01.png");
    background-position: 472px 42px;
    background-size: 2rem;
  }
</style>
