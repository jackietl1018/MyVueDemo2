<template>
  <div class="header">
    <div class="header-left">
      <i class="iconfont back-icon">&#xe614;</i>
    </div>
    <div class="header-input">
      <i class="iconfont">&#xe616;</i>
      <span>输入城市/景点/游玩主题</span>
    </div>
    <router-link></router-link>
      <div class="header-right">城市</div>
  </div>
</template>
<script>
  export default {
    name: 'HomeHeader',
    data() {
      return {

      }
    },
    computed: {},
    created() { },
    methods: {}
  }
</script>
<style lang="stylus" scoped>
  .header 
    display: flex 
    height: 44px
    background: #00bcd4 
    color: #fff 
  .header-left 
    width: 44px
    height: 44px
    line-height: 44px
    float: left 
    .back-icon
      margin-left: 14px
  .header-input 
    flex: 1 
    height: 30px
    line-height 30px 
    margin-left: auto  
    margin-top: 7px 
    background: #ffffff 
    border-radius: 1px 
    color: #ccc 
  .iconfont
    float: left
    margin-left: 8px
  .iconfont span 
    float: left
  .header-right 
    width: 66px
    height: 44px
    line-height: 44px
    float: right 
    text-align : center
</style>