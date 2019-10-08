<template>
  <div class="icons">
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt="">
      </div>
      <p class="icon-desc">景点门票</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/76/eb88861d78fb9902.png" alt="">
      </div>
      <p class="icon-desc">泡温泉</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt="">
      </div>
      <p class="icon-desc">成都必游</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt="">
      </div>
      <p class="icon-desc">川剧变脸</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt="">
      </div>
      <p class="icon-desc">打卡圣地</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt="">
      </div>
      <p class="icon-desc">赏秋色</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt="">
      </div>
      <p class="icon-desc">一日游</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt="">
      </div>
      <p class="icon-desc">成都熊猫</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt="">
      </div>
      <p class="icon-desc">热门景点</p>
    </div>
  </div>
</template>
<script>
export default{
    name:'HomeIcons'
}
</script>
<style lang="stylus" scoped>
    .icons
        width 100%
        overflow hidden
        height 0
        padding-bottom 50%
        .icon
            position relative 
            overflow hidden
            float left 
            width 25%
            height 0
            padding-bottom 25%
            .icon-img
                position absolute 
                top 0
                left 0
                right 0
                bottom 20px
                box-sizing border-box
                padding 2px
                .icon-img-content
                    display block
                    margin 0 auto 
                    height 100%
            .icon-desc
                position absolute 
                left 0
                right 0
                bottom 0
                height 2px
                line-height 2px
                text-align center
                color gray
</style>