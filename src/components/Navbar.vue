<template>
	<div>
		<div id="nav-l" class="uk-position-relative">
			<!-- <home></home> -->
    		<div class="uk-position-top">
        		<!-- <nav class="uk-navbar-container uk-navbar-transparent " uk-navbar> -->
					<nav class="uk-navbar-container uk-navbar-transparent " uk-scrollspy-nav="scroll: true;offset: 80;closest: li;" 
					uk-sticky="bottom: true" uk-navbar>

				<!-- Menus -->
					<div class="uk-navbar-center">
						
							<ul class="uk-navbar-nav">
								<li><a href="#profile">Nosotros</a></li>
								<li><a href="#gallery">Galería</a></li>
								<a class="uk-navbar-item uk-logo" href="#home">Damaris & Omar</a>
								<li><a href="#story">Historia</a></li>
								<li><a href="#invitation">Invitación</a></li>
							</ul>
					</div>
				</nav>
			</div>
		</div>
		<!-- if -->
		<!-- <home></home> -->
		<nav class="uk-navbar-container uk-margin uk-box-shadow-medium uk-hidden@l nav-m" uk-scrollspy-nav="scroll: true;offset: 80;closest: li;" uk-sticky="bottom: body" uk-navbar="mode: click">

			<a class="uk-navbar-item uk-logo" href="#home">Damaris <i class="uk-padding-medium" uk-icon="icon: heart"></i> Omar</a>
			<div class="uk-navbar-right uk-padding-small uk-padding-remove-vertical">
				<ul class="uk-navbar-nav">
			        <li>
			        	<a class="uk-navbar-toggle" uk-navbar-toggle-icon></a>
				        <div class="uk-navbar-dropdown">
				            <ul class="uk-nav uk-navbar-dropdown-nav">
								<li><a href="#profile">Nosotros</a></li>
								<li><a href="#gallery">Galería</a></li>
								<li><a href="#story">Historia</a></li>
								<li><a href="#invitation">Invitación</a></li>
							</ul>
				        </div>
				    </li>
				</ul>
			</div>
		</nav>

	</div>
</template>

<script>
import $ from 'jquery';
import home from '../components/Home';
// import Home from './Home.vue';
export default {
  components: { home },
  name: 'Navbar',

  mounted: function(){
  	if ($(window).width() < 1024 ) {
  		$('#nav-l').remove()
  	}
  }
}
</script>

<style lang="scss" scoped>
  	$colorprimary : #a17188;

	.uk-sticky-placeholder {
		margin: 0 !important;
	}
	.uk-navbar-container {
		background: '' ;
	}
	.uk-navbar-nav > li > a {
		color: #46141d !important;
	}
	.uk-navbar-nav > li > a:hover, .uk-navbar-nav > li > a:focus  {
		color: #000000 !important;
	}
	.uk-navbar-item.uk-logo {
		color: #bc949d !important;
	}
	.uk-logo:hover, .uk-logo:focus {
		color: #5e1c1c !important;
	}
	.uk-navbar-item.uk-logo:after {
		border-top: 35px solid $colorprimary !important;
		position: absolute !important;
		top: 100% !important;
		left: 0 !important;
		content: "";
	}

	@media screen and (max-width: 1024px) {
		.uk-navbar-dropdown-nav > li > a {
			color: #a17188 !important;
		}
		.uk-navbar-dropdown-nav > li > a:hover, .uk-navbar-dropdown-nav > li > a:focus {
			color: #000000 !important;
		}
		.uk-navbar-item.uk-logo:after {
			border-top: 40px solid transparent !important;
			border-left: 108px solid transparent !important;
			border-right: 108px solid transparent !important;
			position: relative !important;
			top: 100% !important;
			left: 0 !important;
			content: "";
		}
		.uk-navbar-dropdown {
			width: 100%;
			left: 0 !important;
			top: 65px !important;
		}
	}
</style>