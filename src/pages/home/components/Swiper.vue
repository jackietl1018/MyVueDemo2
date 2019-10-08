<template>
    <div class="wrapper">
        <swiper :options="swiperOption" >
            <swiper-slide v-for="item of swiperList" :key="item.id">
                <img class="swiper-img" :src="item.imgUrl" alt="">
            </swiper-slide>
            <div class="swiper-pagination"  slot="pagination"></div>
        </swiper>
    </div> 
</template>
<script>
export default {
    name:'HomeSwiper',
    data () {
        return {
            swiperOption:{
                pagination: '.swiper-pagination',
                paginationClickable:true,      //这行使得点击轮播图里小圆点时，能够滑动
                speed:1000,                    //点击小圆点滑动的速度为1000毫秒（1秒）
                autoplayDisableOnInteraction : false,     //点击小圆点时，仍然不影响自动轮播。默认是true，可以试试把这行代码注释掉的效果
                autoplay:1500,                 //自动播放，每隔1.5秒播下一张图片
                loop: true
            },
            swiperList: [
                {
                    id: '0001',
                    imgUrl: 'http://img1.qunarzz.com/piao/fusion/1810/e0/c99056cd01148902.jpg_750x200_8b93d0b5.jpg'
                },
                {
                    id: '0002',
                    imgUrl: 'http://img1.qunarzz.com/piao/fusion/1808/7e/19b06067afac3402.jpg_750x200_f613313a.jpg'
                },
                {
                    id: '0003',
                    imgUrl: 'http://img1.qunarzz.com/piao/fusion/1809/2d/0d7dc3400a50b502.jpg_750x200_4ca95dd4.jpg'
                }
            ]
        }
    }
}
</script>
<style lang="stylus" scoped>
    .wrapper >>> .swiper-pagination-bullet-active
        background #ffffff
    .wrapper
        width 100%
        height 0
        overflow hidden
        padding-bottom 26.66%
        background #eeeeee
        // height 31.25vw (浏览器有差异，不建议)
        .swiper-img
            width 100% 
</style>