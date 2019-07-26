<template>
  <div class="home">
    <div class="top">
      <div><img src="../assets/logo.png" class="logo"/></div>      
      <p class="city">
        <img src="../assets/1.png" alt="">重庆
      </p>
    </div>
    <div class="kv">柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
    <div>柯文</div>
  </div>
</template>

<script>
import { Indicator } from "mint-ui"
// @ is an alias to /src
import axios from 'axios'
export default {
  name: 'home',
  components: {},
  methods: {
    
  },
  created() {
    axios.get('https://www.easy-mock.com/mock/5b8fab1d06b4621da8247b00/example/singer_list').then(res => {
      console.log('res: ', res)
    })
  }
}
</script>

<style lang="scss">
.kv{
  font-size: px2rem(16);
}
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

