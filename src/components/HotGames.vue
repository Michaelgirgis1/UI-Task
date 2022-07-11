<template>
  <div class="hot-games container">
    <h2 class="section-title">Hot Games</h2>
    <swiper :options="hotGamesSliderOption">
      <swiper-slide>
        <div class="hot-games__item">
          <img src="./../assets/hot-games/hot-games-1.png" alt="" srcset="">
        </div>
      </swiper-slide>
      <swiper-slide>  
        <div class="hot-games__item">
          <img src="./../assets/hot-games/hot-games-2.png" alt="" srcset="">
        </div></swiper-slide>
      <swiper-slide>
        <div class="hot-games__item">
          <img src="./../assets/hot-games/hot-games-3.png" alt="" srcset="">
        </div>
      </swiper-slide>
      <swiper-slide>
        <div class="hot-games__item">
          <img src="./../assets/hot-games/hot-games-4.png" alt="" srcset="">
        </div>
      </swiper-slide>
      <swiper-slide>
        <div class="hot-games__item">
          <img src="./../assets/hot-games/hot-games-5.png" alt="" srcset="">
        </div>
      </swiper-slide>

    </swiper>
  </div>
</template>

<script>
import { Swiper, SwiperSlide } from "vue-awesome-swiper";
import "swiper/css/swiper.css";
export default {
  data() {
    return {
      hotGamesSliderOption: {
        slidesPerView: 4.4,
        spaceBetween: 12
      },
    };
  },
  components: {
    Swiper,
    SwiperSlide,
  },
};
</script>

<style lang="scss">
.hot-games {
  margin-bottom: 15px;
  &.container {
    padding-inline-end: 0;
  }

  .hot-games__item {
    img {
      max-width: 100%;
    border-radius: 10px;
    }
  }
}
</style>