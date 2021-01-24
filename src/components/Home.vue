<template>
  <div
    id="home"
    class="uk-background-cover uk-overflow-hidden uk-padding-large uk-padding-remove-bottom uk-padding-remove-horizontal"
  >
    <!-- Imagen -->
    <div class="uk-flex uk-visible@l">
      <div
        class="uk-card uk-animation-slide-bottom-medium uk-width-xlarge"
        uk-parallax="target: #home; y: 250; sepia: 40;easing: 0;"
        style="height: calc(100vh - 150px)"
      >
        <!-- <img src="../assets/images/image2.png" alt="Couple" class="uk-padding-small uk-padding-remove-top"> -->
      </div>
      <!-- Texto -->
      <div
        class="uk-width-expand uk-margin-auto uk-margin-auto-vertical uk-padding-small"
      >
        <h1
          class="uk-text-center uk-h1 uk-animation-slide-top home"
          uk-parallax="target: #home; y: 300;blur: 0,05;easing: 0;"
        >
          {{ title }}
        </h1>
        <p
          class="uk-text-center uk-padding-large uk-animation-slide-top uk-padding-remove-top uk-padding-remove-bottom uk-h3 home"
          uk-parallax="target: #home; y: 200; blur: 0,05;easing: 0;"
        >
          {{ deskripsi }}
        </p>
        <p
          class="uk-text-center uk-padding-large uk-animation-slide-top uk-padding-remove-top uk-padding-remove-bottom uk-h3 home"
          uk-parallax="target: #home; y: 200; blur: 0,05;easing: 0;"
        >
          {{ lugar }}
        </p>

        <!-- Countdown -->
        <!-- uk-parallax="target: #home; y: 200; blur: 0,05;easing: 0;" -->
        <div
          class="uk-responsive-width uk-padding-large uk-padding-remove-bottom home"
        >
          <div class="countdown uk-flex uk-visible@l">
            <div
              uk-grid
              uk-countdown="date: 2021-10-09T11:17:00+00:00"
              class="uk-margin-auto"
            >
              <div>
                <div class="uk-countdown-number uk-countdown-days"></div>
                <div class="uk-countdown-label uk-margin-small uk-text-center">
                  Días
                </div>
              </div>
              <div class="uk-countdown-separator">:</div>
              <div>
                <div class="uk-countdown-number uk-countdown-hours"></div>
                <div class="uk-countdown-label uk-margin-small uk-text-center">
                  Horas
                </div>
              </div>
              <div class="uk-countdown-separator">:</div>
              <div>
                <div class="uk-countdown-number uk-countdown-minutes"></div>
                <div class="uk-countdown-label uk-margin-small uk-text-center">
                  Minutos
                </div>
              </div>
              <div class="uk-countdown-separator">:</div>
              <div>
                  <div class="uk-countdown-number uk-countdown-seconds"></div>
                  <div class="uk-countdown-label uk-margin-small uk-text-center">Segundos</div>
               </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Movimiento -->
    <div class="uk-overflow-hidden uk-hidden@l">
      <div
        class="uk-card uk-responsive-height uk-animation-slide-bottom-medium"
        uk-parallax="target: #home; y: 600; sepia: 40;easing: 0;"
      >
      </div>

      <div
        class="uk-responsive-width uk-margin-auto uk-margin-auto-vertical uk-padding-medium"
      >
        <h1
          class="uk-text-center uk-h1 uk-animation-slide-top home"
          uk-parallax="target: #home; y: 300;blur: 0,05;easing: 0;"
        >
          {{ title }}
        </h1>
        <p
          class="uk-text-center uk-padding-large uk-animation-slide-top uk-padding-remove-top uk-h3 home"
          uk-parallax="target: #profile; y: 200; blur: 0,05;easing: 0;"
        >
          {{ deskripsi }}
        </p>
      </div>
    </div>
  </div>
  <!--  // 'https://4.bp.blogspot.com/-Vkv1EpmPF7E/Wi3whl0qf3I/AAAAAAAAH88/Km_GQFM6JyYX-9-ue7aCMKUjV9BNc0_sQCLcBGAs/s1600/bg.jpg' -->
</template>

<script>
export default {
  name: "Home",

  data() {
    return {
      title: "Damaris & Omar",
      deskripsi: "Octubre 9, 2021, 5 pm ",
      lugar: " Xochicihuatl, Puebla"
    };
  },
};
</script>

<style lang="scss" scoped>
$colorprimary: #a17188;

#home {
  background-image: url("../assets/images/foto1.jpg");
  mix-blend-mode: multiply !important;
   max-width: 100%;
  height: auto;
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.home {
  color: #523543 !important;
}
.uk-h1 {
  font-size: 120px !important;
}
.countdown * {
  font-size: 80px !important;
  // color: $colorprimary !important;
}
.uk-countdown-number,
.uk-countdown-separator {
  line-height: 1 !important;
}
.countdown .uk-countdown-label {
  font-size: 30px !important;
}
.countdown .uk-grid > * {
  padding-left: 20px !important;
}

@media screen and (max-width: 1024px) {
  #home {
    margin-bottom: 0px !important;
  }
  .uk-h1 {
    font-size: 47px !important;
  }
}
</style>