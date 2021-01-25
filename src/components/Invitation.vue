<template>
  <div id="invitation">
    <h1
      class="uk-heading-line uk-text-center uk-h1 uk-padding-small title"
      uk-scrollspy="cls:uk-animation-slide-top-small"
    >
      <span>Estas invitado</span>
    </h1>

    <div class="uk-container uk-container-large">
      <div class="uk-child-width-1-2@s" uk-grid>
        <div>
          <div class="uk-card uk-card-default uk-card-large uk-card-body">
            <img src="../assets/images/invitation.jpeg" alt="" />
          </div>
        </div>
        <div>
          <div class="uk-card uk-card-default uk-card-large uk-card-body">
            <div class="uk-card-body">
              <b>¿Cómo llegar?</b>
              <a
                class="uk-button uk-button-small"
                href="https://goo.gl/maps/twDB6fCF2hF1ipgi7"
                target="_blank"
                ><img
                  title="Hacienda Xochicihuatl"
                  uk-tooltip="pos: bottom"
                  class="uk-width-1-4"
                  src="../assets/images/mapa.png"
                  alt="Mapa"
              /></a>
              <br />
              <b>¿Dónde hospedarse?</b>
              <a class="uk-button uk-button-small"
                ><img
                  title="Hacienda Xochicihuatl"
                  uk-tooltip="pos: bottom"
                  class="uk-width-1-4"
                  src="../assets/images/hotel.png"
                  alt="Hotel"
              /></a>
              <p>
                VILLAS TENEX: Carr a Tenextepec (244-103-7205), La Soledad,
                74365, Atlixco, Puebla
              </p>
              <p>Hostal Imagina (55-9197-7610) , Atlixco, Puebla</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>



<script>
export default {
  name: "Invitation",
};
</script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Handlee&display=swap");
$colorprimary: #a17188;
body h2 p,
.uk-logo {
  font-family: "Handlee", cursive !important;
  font-size: 35px !important;
}

#invitation {
  padding-top: 1px;
  padding-bottom: 50px;
  background-color: #ffffff;
}
.countdown * {
  font-size: 30px !important;
  color: $colorprimary !important;
}
.uk-countdown-number,
.uk-countdown-separator {
  line-height: 1 !important;
}
.countdown .uk-countdown-label {
  font-size: 20px !important;
}
.countdown .uk-grid > * {
  padding-left: 10px !important;
}
.text-nama {
  padding-top: 10px;
  padding-bottom: 10px !important;
}
.text-nama h1 {
  font-size: 50px !important;
  margin: 0 !important;
}
.text-nama h5,
.text-nama h3 {
  margin: 0 !important;
}
.text-nama p,
.text-nama h4 {
  padding-top: 10px !important;
  padding-bottom: 10px !important;
}
.uk-width-1-4 {
  padding: 0 !important;
  margin: 0 !important;
}
h4 {
  margin-top: 15px !important;
}
h5 {
  color: #666666 !important;
}
.uk-card-body {
  font-family: "Handlee", cursive !important;
  font-size: 20px !important;
  border-style: solid;
  border-color: $colorprimary;
}

@media screen and (max-width: 1024px) {
  .countdown * {
    font-size: 20px !important;
    color: $colorprimary !important;
  }
  .uk-countdown-number,
  .uk-countdown-separator {
    line-height: 1 !important;
  }
  .countdown .uk-countdown-label {
    font-size: 12px !important;
  }
  .countdown .uk-grid > * {
    padding-left: 5px !important;
  }
  .text-nama h1 {
    font-size: 27px !important;
  }
  .text-nama h5 {
    font-size: 12px !important;
  }
}
</style>
