<template>
    <div class="icons">
      <swiper class="wrapper" :options="swiperOption">
        <swiper-slide>
          <div class="icon">
            <img class="img-icon" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt=""/>
            <p class="icon-desc">景点门票</p>
          </div>
          <div class="icon">
            <img class="img-icon" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt=""/>
            <p class="icon-desc">景点门票</p>
          </div>
          <div class="icon">
            <img class="img-icon" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt=""/>
            <p class="icon-desc">景点门票</p>
          </div>
          <div class="icon">
            <img class="img-icon" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt=""/>
            <p class="icon-desc">景点门票</p>
          </div>
          <div class="icon">
            <img class="img-icon" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt=""/>
            <p class="icon-desc">景点门票</p>
          </div>
          <div class="icon">
            <img class="img-icon" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt=""/>
            <p class="icon-desc">景点门票</p>
          </div>
          <div class="icon">
            <img class="img-icon" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt=""/>
            <p class="icon-desc">景点门票</p>
          </div>
          <div class="icon">
            <img class="img-icon" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt=""/>
            <p class="icon-desc">景点门票</p>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="icon">
            <img class="img-icon" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png" alt=""/>
            <p class="icon-desc">景点门票</p>
          </div>
        </swiper-slide>
      </swiper>
    </div>
</template>

<script>
export default {
  name: 'HomeIcons',
  data () {
    return {
      swiperOption: {
        autoplay: false
      }
    }
  }
}
</script>

<style lang="stylus" scoped>
  @import "~styles/mixins.styl"
  .icons
    width 100%
    overflow hidden
    height 3.2rem
    .wrapper
      height 3.2rem
      .icon
        float: left;
        width: 25%;
        height: 1.5rem;
        padding-top: .1rem;
        text-align: center;
        .img-icon
          display block
          margin 0 auto
          height 1.1rem
          width 1.1rem
        .icon-desc
          text-align center
          ellipsis()
</style>
