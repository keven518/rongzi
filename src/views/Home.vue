<template>
  <div class="home">
    <div class="top">
      <div><img src="../assets/logo.png" class="logo"/></div>      
      <p class="city">
        <img src="../assets/1.png" alt="">重庆
      </p>
    </div>
  </div>
</template>

<script>
import { Indicator } from "mint-ui"
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  },
  methods: {
    
  },
  created() {
    // Indicator.open('cmm');
  }
}
</script>

<style lang="scss">
.home {
  .top{
    position: relative;
    height: px2rem(48);
    padding: px2rem(14) 0 0 px2rem(14);
    box-sizing: border-box;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    .logo{
      width: px2rem(104);
    }
    .city{
      position: absolute;
      z-index: 2;
      top: .54rem;
      right: 6.4px;
      right: .4rem;
      color: #999;
      height: px2rem(24);
      padding: .96px 3.84px 0;
      padding: .06rem .24rem 0;
      background: #e8e8ea;
      font-size: 5.12px;
      font-size: .32rem;
      border-radius: .27rem;
      img{
        height: px2rem(14);
      }
    }
  }
}
</style>

