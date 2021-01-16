<template>
  <div id="gallery">
    <h1
      class="uk-heading-line uk-text-center uk-h1 uk-padding-medium title"
      uk-scrollspy="cls:uk-animation-slide-top-small"
    >
      <span>Galería</span>
    </h1>



    <!-- <div
      class="uk-responsive-width uk-padding-small uk-overflow-hidden uk-padding-remove-top"
      uk-scrollspy="cls:uk-animation-slide-top-small"
    > -->
      <!-- Video de youtube -->
      <!-- <iframe
        src="https://www.youtube.com/embed/eay_NdtmJVM?autoplay=0&amp;showinfo=0&amp;rel=0&amp;modestbranding=1&amp;playsinline=1"
        width="800"
        height="500"
        frameborder="0"
        gesture="media"
        allow="encrypted-media"
        allowfullscreen
        uk-responsive
      ></iframe> -->
      <!-- Carrousel -->
      <!-- Checar las buenas imagenes en pantallazo -->
      <!-- <div class="uk-padding-remove-top slider">
        <slick ref="slick" :options="slickOptions"> -->
<!-- 
          <div class="uk-position-relative uk-visible-toggle uk-light" tabindex="-1" uk-slider>

    <ul class="uk-slider-items uk-child-width-1-2 uk-child-width-1-3@s uk-child-width-1-4@m"> -->

          <!-- <div class="uk-responsive-width uk-responsive-height uk-padding-small">
              <img class="uk-height-medium" src="../assets/images/image1.jpeg" alt="foto1">
            </div>
            <div class="uk-responsive-width uk-responsive-height uk-padding-small">
              <img class="uk-height-medium" src="../assets/images/image3.jpg" alt="foto3">
            </div> 
            <div class="uk-responsive-width uk-responsive-height uk-padding-small">
              <img class="uk-height-medium " src="../assets/images/image4.jpg" alt="foto4">
            </div>
            <div class="uk-responsive-width uk-responsive-height uk-padding-small">
              <img class="uk-height-medium " src="../assets/images/image4.jpg" alt="foto4">
            </div> -->
          
       <!-- <li>
            <img src="../assets/images/image1.jpeg" alt="">
            <div class="uk-position-center uk-panel"><h1>1</h1></div>
        </li>
        <li>
            <img src="../assets/images/image3.jpg" alt="">
            <div class="uk-position-center uk-panel"><h1>2</h1></div>
        </li>
        <li>
            <img src="../assets/images/image4.jpg" alt="">
            <div class="uk-position-center uk-panel"><h1>3</h1></div>
        </li>
    </ul>

    </div> -->
  <!-- <div class="uk-child-width-1-2@m" uk-grid > -->
          <!-- <div class="uk-responsive-width uk-padding-large uk-overflow-hidden uk-grid-collapse uk-visible@l uk-child-width-1-2 uk-position-relative" uk-grid> -->
<div>

<div class="block w-0 min-w-full">
     <VueSlickCarousel v-bind="settings">
       <div>     <img src="../assets/images/image6.jpg" style="max-width:100%;width:auto;height:auto;" 
            sizes="(max-width: 400px) 300px, (max-width: 1200px) 1000px, 2000px"/> </div>
       <div>     <img src="../assets/images/image7.jpg" style="max-width:100%;width:auto;height:auto;" 
            sizes="(max-width: 400px) 300px, (max-width: 1200px) 1000px, 2000px"/> </div>
       <div>     <img src="../assets/images/image10.jpg" style="max-width:100%;width:auto;height:auto;" 
            sizes="(max-width: 400px) 300px, (max-width: 1200px) 1000px, 2000px"/> </div>
    </VueSlickCarousel> 

        </div>

</div>

    <!-- El slide -->
<!-- 
   
        <div class="uk-slidenav-position"
          uk-slideshow="autoplay:true autoplay-interval:1000">

    <ul class="uk-slideshow-items">
        <li>
            <img src="../assets/images/image6.jpg"  alt=""  uk-cover uk-img="target: !ul > :last-child, !* +*">

        </li>
        <li>
            <img src="../assets/images/image10.jpg"  alt="" uk-cover uk-img="target: !* -*, !* +*">
        </li>
        <li>
            <img src="../assets/images/image7.jpg" alt="" uk-cover uk-img="target: !* -*, !ul > :first-child">
        </li>
    </ul>

</div> -->
      <!-- LA presentacion -->
<!-- <div class="block w-0 min-w-full">
     <VueSlickCarousel v-bind="settings">
       <div>     <img src="../assets/images/image6.jpeg" style="max-width:100%;width:auto;height:auto;" 
            sizes="(max-width: 400px) 300px, (max-width: 1200px) 1000px, 2000px"/> </div>
       <div>     <img src="../assets/images/image7.jpg" style="max-width:100%;width:auto;height:auto;" 
            sizes="(max-width: 400px) 300px, (max-width: 1200px) 1000px, 2000px"/> </div>
       <div>     <img src="../assets/images/image10.jpg" style="max-width:100%;width:auto;height:auto;" 
            sizes="(max-width: 400px) 300px, (max-width: 1200px) 1000px, 2000px"/> </div>
    </VueSlickCarousel> 

        </div> -->


      <!-- La presenracion -->

<!-- <div class="block w-0 min-w-full">
     <VueSlickCarousel v-bind="settings2">
       <div>
          
                            <h3 class="uk-margin-remove">Damaris</h3>
          <img src="../assets/images/novia1.jpg" style="max-width:100%;width:auto;height:auto;" 
            sizes="(max-width: 400px) 300px, (max-width: 1200px) 1000px, 2000px"
            
            /> 

           <div class="uk-overlay uk-overlay-primary uk-position-bottom uk-text-center uk-transition-slide-bottom">
                <p class="uk-margin-remove">Poblana</p>
            </div>
           
        </div>
        <div>
          
                            <h3 class="uk-margin-remove">Omar</h3>
          <img src="../assets/images/novio1.jpg" style="" 
            sizes="(max-width: 400px) 300px, (max-width: 1200px) 1000px, 2000px"
            
            /> 

           <div class="uk-overlay uk-overlay-primary uk-position-bottom uk-text-center uk-transition-slide-bottom">
                <p class="uk-margin-remove">Poblana</p>
            </div>
           
        </div>
          
       
    </VueSlickCarousel> 

        </div> -->




<!--        
  <div class="uk-slidenav-position  "
        uk-slideshow="autoplay: true;  animation:push; "
         > 
      <ul class="uk-slideshow-items">
        <li>
            <img src="../assets/images/novia1.jpg" alt="" uk-cover  style="max-width:100%;width:auto;height:auto;" 
            sizes="(max-width: 400px) 300px, (max-width: 1200px) 1000px, 2000px"
            >
            <div class="uk-overlay uk-overlay-primary uk-position-bottom uk-text-center uk-transition-slide-bottom">
                <h3 class="uk-margin-remove">Damaris</h3>
                <p class="uk-margin-remove">Poblana</p>
            </div>
        </li>
        <li>
            <img src="../assets/images/novio1.jpg" alt="" uk-cover  style="max-width:100%;width:auto;height:auto;" 
            sizes="(max-width: 400px) 300px, (max-width: 1200px) 1000px, 2000px">
            <div class="uk-overlay uk-overlay-primary uk-position-bottom uk-text-center uk-transition-slide-bottom">
                <h3 class="uk-margin-remove">Omar</h3>
                <p class="uk-margin-remove">Guadalajareño</p>
            </div>
        </li>
    </ul>


  </div>  -->

<!-- <div class="uk-position-relative uk-visible-toggle uk-light" tabindex="-1" uk-slider="clsActivated: uk-transition-active; center: true">

    <ul class="uk-slider-items uk-grid">
              <li class="uk-width-1-3">

            <div class="uk-panel">
                <img src="../assets/images/novia1.jpg" alt="">
                <div class="uk-overlay uk-overlay-primary uk-position-bottom uk-text-center uk-transition-slide-bottom">
                    <h3 class="uk-margin-remove">Bottom</h3>
                    <p class="uk-margin-remove">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                </div>
            </div>
        </li>
        <li class="uk-width-1-2">
            <div class="uk-panel">
                <img src="../assets/images/novio1.jpg" alt="">
                <div class="uk-overlay uk-overlay-primary uk-position-bottom uk-text-center uk-transition-slide-bottom">
                    <h3 class="uk-margin-remove">Bottom</h3>
                    <p class="uk-margin-remove">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                </div>
            </div>
        </li>
        
    </ul>

    <a class="uk-position-center-left uk-position-small uk-hidden-hover" href="#" uk-slidenav-previous uk-slider-item="previous"></a>
    <a class="uk-position-center-right uk-position-small uk-hidden-hover" href="#" uk-slidenav-next uk-slider-item="next"></a>

</div> -->




    </div>



</template>

<script>
import Slick from "vue-slick";
import "slick-carousel/slick/slick.css";
import "slick-carousel/slick/slick-theme.css";

import VueSlickCarousel from 'vue-slick-carousel'
  import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'


export default {
  name: "Gallery",
  components: { VueSlickCarousel  },

  data() {
    return {
      settings:{
          
       "lazyLoad": "ondemand",
        "dots": true,
        "fade": true,
        "infinite": true,
        "speed": 500,
        "slidesToShow": 1,
        "slidesToScroll": 1,
        "autoplay": true,
        "speed": 2000,
        "autoplaySpeed": 2000,
        "centerMode": true,
        "centerPadding": "20px",
        "min-height": 0,
        "min-width": 0,
        "arrows":false,
        "adaptiveHeight": false,
        "heigth": 100
      }
      ,
      settings2:{
          
       "lazyLoad": "ondemand",
        "infinite": true,
        "speed": 500,
        "slidesToShow": 1,
        "slidesToScroll": 1,
        "autoplay": true,
        "speed": 2000,
        "autoplaySpeed": 3000,
        "cssEase": "linear",
        "centerMode": true,
        "centerPadding": "20px",
        "swipeToSlide": true,
        "min-height": 0,
        "min-width": 0,
        "arrows":false,
        "adaptiveHeight": false


      },
      slickOptions: {
        infinite: true,
        slidesToShow: 3,
        slidesToScroll: 3,
        dots: true,
        speed: 2000,
        autoplay: true,
        autoplaySpeed: 2000,
        responsive: [
          {
            breakpoint: 1024,
            settings: {
              slidesToShow: 3,
              slidesToScroll: 3,
              infinite: true,
              dots: true,
            },
          },
          {
            breakpoint: 600,
            settings: {
              slidesToShow: 2,
              slidesToScroll: 2,
              infinite: true,
              dots: true,
            },
          },
          {
            breakpoint: 480,
            settings: {
              slidesToShow: 1,
              slidesToScroll: 1,
              infinite: true,
              dots: false,
              fade: true,
              cssEase: "linear",
            },
          },
        ],
      },
      //imgUrl: "../assets/images/novio1.jpg"
    };
  },
};

</script>

<style lang="css" scoped>
#gallery {
  padding-top: 1px;
  background-color: #c7c8ce;
}
.slider {
  padding: 5px;
}
.carousel {
width:640;
height:320;
  background-color: #ccc;
}
@media screen and (max-width: 1024px) {
  .slider {
    padding: 3px;
  }
}
</style>