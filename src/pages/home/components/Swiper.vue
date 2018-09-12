<template>
  <swiper class="wrapper" :options="swiperOption">
    <!-- slides -->
    <swiper-slide>
      <img class="swiper-img" :src="logo1" alt="">
    </swiper-slide>
    <swiper-slide>
      <img class="swiper-img" :src="logo2" alt="">
    </swiper-slide>
    <!-- Optional controls -->
    <div class="swiper-pagination"  slot="pagination"></div>
  </swiper>
</template>

<script>
export default {
  name: 'HomeSwiper',
  data () {
    return {
      logo1: require('/Travel/static/img/swiper1.jpg'),
      logo2: require('/Travel/static/img/swiper2.jpg'),
      swiperOption: {
        pagination: '.swiper-pagination'
      }
    }
  }
}
</script>

<style lang="stylus" scoped>
  .wrapper
    width 100%
    height 0;
    overflow hidden
    padding-bottom 4rem
    background #eee
  .wrapper >>> .swiper-pagination-bullet-active
    background #fff
  .swiper-img
    width 100%
    height 4rem

</style>
