  

<template>
	<div id="invitation">
    <h1
      class="uk-heading-line uk-text-center uk-h1 uk-padding-small title"
      uk-scrollspy="cls:uk-animation-slide-top-small"
    >
      <span>Mesa de regalos</span>
    </h1>
	<!-- <div class="uk-child-width-1-4@m" uk-grid>
    <div>
        <div class="uk-card uk-card-default">
            <div class="uk-card-media-top">
                <img src="../assets/images/invitation.jpeg" alt="">
            </div>
            <div class="uk-card-body">
                <h3 class="uk-card-title">Media Top</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
            </div>
        </div>
    </div>
    <div>
        <div class="uk-card uk-card-default">
            <div class="uk-card-body">
                <h3 class="uk-card-title">Media Bottom</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
            </div>
            <div class="uk-card-media-bottom">
                <img src="../assets/images/invitation.jpeg" alt="">
            </div>
        </div>
		<div class="uk-card uk-card-default">
            <div class="uk-card-media-top">
                <img src="../assets/images/invitation.jpeg" alt="">
            </div>
            <div class="uk-card-body">
                <h3 class="uk-card-title">Media Top</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
            </div>
        </div>
    </div>
    <div>
        <div class="uk-card uk-card-default">
            <div class="uk-card-body">
                <h3 class="uk-card-title">Media Bottom</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
            </div>
            <div class="uk-card-media-bottom">
                <img src="../assets/images/invitation.jpeg" alt="">
            </div>
        </div>
    </div> -->
		
     <div class="uk-container uk-container-small">
      <div class="uk-child-width-1-1@s" uk-grid>
        <div>
			 
          <div class="uk-card uk-card-default uk-card-large uk-card-body uk-align-left@s">
        		<p>El regalo es opcional<br> NOS ENCANTARÍA QUE NOS ACOMPAÑARAS <br>pero si quieres tener un detalle con nosotros <br> dona para nuestra LUNA DE MIEL.</p>
				<form action="https://www.paypal.com/donate" method="post" target="_top">
<input type="hidden" name="hosted_button_id" value="HF5Z64SC4XNWL" />
<input type="image" src="https://www.paypalobjects.com/es_XC/MX/i/btn/btn_donateCC_LG.gif" border="0" name="submit" title="Coopera para la luna de miel" alt="Cooperar" />
<img alt="" border="0" src="https://www.paypal.com/es_MX/i/scr/pixel.gif" width="1" height="1" />
</form>


			</div>
			
        </div>
	  </div>
	</div>
</div>
	
	
	
	

	  


<!-- 
    
    <img class="uk-border-pill" src="../assets/images/story3.jpeg" alt="">
    <img class="uk-border-pill" src="../assets/images/story1.jpeg" alt=""> -->

</div>


	</div>
</template>


<script>
export default {
  name: "Profile",
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

#Profile {
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
