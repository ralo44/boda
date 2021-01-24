<template>
  <div id="story">
    <h1 class="uk-heading-line uk-text-center uk-h1 uk-padding-small title" uk-scrollspy="cls:uk-animation-slide-top-small"><span>Nuestra historia</span></h1>

      <div class="uk-responsive-width uk-padding-large uk-overflow-hidden uk-grid-collapse uk-visible@l uk-child-width-1-2 uk-position-relative" uk-grid>
      
        <div class="garis-vertical"></div>
        
        <!-- uno -->
        <div class="uk-padding-small" uk-scrollspy="cls: uk-animation-slide-left-medium; repeat: true">
          <img class="uk-border-pill" src="../assets/images/story1.jpeg" alt="">
        </div>
        <div class="uk-padding-small">
          <div class="uk-card uk-card-default uk-card-hover">
            <!-- <div class="bulet-kanan"></div> -->
            <div class="uk-card-header uk-card-primary">
                <div class="uk-grid-small uk-flex-middle" uk-grid>
                    <div class="uk-width-expand">
                        <h3 class="uk-card-title uk-margin-remove-bottom uk-text-bold">
                          9 de Abril 2017
                        </h3>
                    </div>
                </div>
            </div>
            <div class="uk-card-body">
              <p>Nos conocimos en la playa de Varadero, Cuba. Por azhares del destino en un viaje de amigos donde tuvimos la oportunidad de platicar.  </p>
            </div>
          </div>
        </div>
        <!-- Dos   -->
        <div class="uk-padding-small">
          <div class="uk-card uk-card-default uk-card-hover">
            <!-- <div class="bulet-kiri"></div> -->
            <div class="uk-card-header uk-card-primary">
                <div class="uk-grid-small uk-flex-middle" uk-grid>
                    <div class="uk-width-expand">
                        <h3 class="uk-card-title uk-margin-remove-bottom uk-text-bold">
                          2 de Julio 2017
                        </h3>
                    </div>
                </div>
            </div>
            <div class="uk-card-body">
              <p>Despúes de extensas llamadas por telefono, al fin nos volvimos a encontrar pero ahora en México. </p>
            </div>
          </div>
        </div>
        <div class="uk-padding-small" uk-scrollspy="cls: uk-animation-slide-right-medium; repeat: true">
          <img class="uk-border-pill" src="../assets/images/story2.jpeg" alt="">
        </div>

        <!-- tres -->
        <div class="uk-padding-small" uk-scrollspy="cls: uk-animation-slide-left-medium; repeat: true">
          <img class="uk-border-pill" src="../assets/images/story3.jpeg"  alt="Story 3 Khitbah">
        </div>
        <div class="uk-padding-small">
          <div class="uk-card uk-card-default uk-card-hover">
            <!-- <div class="bulet-kanan"></div> -->
            <div class="uk-card-header uk-card-primary">
                <div class="uk-grid-small uk-flex-middle" uk-grid>
                    <div class="uk-width-expand">
                        <h3 class="uk-card-title uk-margin-remove-bottom uk-text-bold">
                          2 de Octubre de 2020
                        </h3>
                    </div>
                </div>
            </div>
            <div class="uk-card-body">
              <p>Despúes de más de tres años de novios, decidimos dar el gran paso y comprometernos para hacer una vida juntos.</p>
            </div>
          </div>
        </div>
      </div>
<!-- Doble -->
       <div class="uk-responsive-width uk-padding-large uk-overflow-hidden uk-grid-collapse uk-hidden@l uk-position-relative" uk-grid>
        <div class="uk-padding-large uk-width-expand" uk-scrollspy="cls: uk-animation-slide-left-medium; repeat: true">
          <img class="uk-border-pill" src="../assets/images/story1.jpeg" alt="Story 1 First Met">
        </div>
        <div class="uk-padding-medium">
          <div class="uk-card uk-card-default uk-card-hover">
            <div class="uk-card-header uk-card-primary">
                <div class="uk-grid-small uk-flex-middle" uk-grid>
                    <div class="uk-width-expand">
                        <h3 class="uk-card-title uk-margin-remove-bottom uk-text-bold">
                                                    9 de Abril 2017

                        </h3>
                    </div>
                </div>
            </div>
            <div class="uk-card-body">
              <p>Nos conocimos en la playa de Varadero, Cuba. Por azhares del destino en un viaje de amigos donde tuvimos la oportunidad de platicar.  </p>
            </div>
          </div>
        </div>
        <div class="uk-padding-large uk-width-expand" uk-scrollspy="cls: uk-animation-slide-right-medium; repeat: true">
          <img class="uk-border-pill" src="../assets/images/story2.jpeg" alt="Story 2 First Dated">
        </div>
        <div class="uk-padding-medium">
          <div class="uk-card uk-card-default uk-card-hover">
            <div class="uk-card-header uk-card-primary">
                <div class="uk-grid-small uk-flex-middle" uk-grid>
                    <div class="uk-width-expand">
                        <h3 class="uk-card-title uk-margin-remove-bottom uk-text-bold">
                          2 de Julio 2017
                        </h3>
                    </div>
                </div>
            </div>
            <div class="uk-card-body">
              <p>Despúes de extensas llamadas por telefono, al fin nos volvimos a encontrar pero ahora en México. </p>
            </div>
          </div>
        </div>
        <div class="uk-padding-large uk-width-expand" uk-scrollspy="cls: uk-animation-slide-left-medium; repeat: true">
          <img class="uk-border-pill"  src="../assets/images/story3.jpeg" alt="Story 3 Khitbah">
        </div>
        <div class="uk-padding-medium">
          <div class="uk-card uk-card-default uk-card-hover">
            <div class="uk-card-header uk-card-primary">
                <div class="uk-grid-small uk-flex-middle" uk-grid>
                    <div class="uk-width-expand">
                        <h3 class="uk-card-title uk-margin-remove-bottom uk-text-bold">
                          2 de Octubre de 2020
                        </h3>
                    </div>
                </div>
            </div>
            <div class="uk-card-body">
              <p>Despúes de más de tres años de novios, decidimos dar el gran paso y comprometernos para hacer una vida juntos.</p>
            </div>
          </div>
        </div>
      </div> 
  </div>
  <!-- 8eac88 el verde
   bc949d  rosita
     986e9e-->
</template>

<script>
export default {
  name: 'Story',
};
</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Handlee&display=swap');
  $colorprimary : #a17188;
  body h1, .uk-logo {
    font-family: 'Handlee', cursive !important;
    font-size: 35px !important;
  }
  
  #story {
    padding-top: 1px;
    background-color: #ffffff;
  } 
  img {
    width: 50%;
  }
  .uk-card-primary {
    background-color: $colorprimary;
    font-family: 'Handlee', cursive !important;
    font-size: 20px !important;
  }
  .uk-card-body {
    font-family: 'Handlee', cursive !important;
    font-size: 20px !important;
    border-style: solid;
    border-color: $colorprimary;
  }
  .garis-vertical {
    position: absolute;
    left: calc(50% - 2px);
    top: 0;
    width: 4px;
    height: 100%;
    background-color: $colorprimary;
    opacity: 0.3;
  }
  .bulet-kanan {
    position: absolute;
    left: calc(-0px + calc(3px / 2));
    top: calc(37px - calc(29px / 2));
    width: 25px;
    height: 25px;
    background: $colorprimary;
    border: 4px solid white;
    border-radius: 100%;
  }
  .bulet-kiri {
    position: absolute;
    right: calc(-73px + calc(-25px / 2));
    top: calc(37px - calc(29px / 2));
    width: 25px;
    height: 25px;
    background: $colorprimary;
    border: 4px solid white;
    border-radius: 100%;
  }

  @media screen and (max-width: 1024px) {
    
  }
</style>