<template>
  <div id="gallery">
    <h1
      class="uk-heading-line uk-text-center uk-h1 uk-padding-medium title"
      uk-scrollspy="cls:uk-animation-slide-top-small"
    >
      <span>Galería</span>
    </h1>
    <div class="uk-container uk-container-small">
      <!-- <div> -->
      <VueSlickCarousel v-bind="settings">
        <div><img src="../assets/images/image11.jpg" /></div>
        <div><img src="../assets/images/image7.jpg" /></div>
        <div><img src="../assets/images/image10.jpg" /></div>
        <div><img src="../assets/images/image12.jpg" /></div>
      </VueSlickCarousel>
    </div>
  </div>
</template>

<script>
import Slick from "vue-slick";
import "slick-carousel/slick/slick.css";
import "slick-carousel/slick/slick-theme.css";

import VueSlickCarousel from "vue-slick-carousel";
import "vue-slick-carousel/dist/vue-slick-carousel-theme.css";

export default {
  name: "Gallery",
  components: { VueSlickCarousel },

  data() {
    return {
      settings: {
        lazyLoad: "ondemand",
        dots: true,
        infinite: true,
        speed: 500,
        slidesToShow: 1,
        slidesToScroll: 1,
        autoplay: true,
        speed: 2000,
        autoplaySpeed: 2000,
      },
    };
  },
};
</script>

<style lang="css" scoped>
#gallery {
  padding-top: 1px;
  background-color: #ffffff;
}

@media screen and (max-width: 1024px) {
}
</style>