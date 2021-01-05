<template>
	<div id="profile">
		<div>
			<h1 class="uk-heading-line uk-text-center uk-h1 uk-padding-small title" uk-scrollspy="cls:uk-animation-slide-top-small"><span>Nosotros</span></h1>
			<div>
				<div class="uk-column-1-2@l uk-padding-large">
					<!-- Novia -->
					<div uk-scrollspy="cls:uk-animation-slide-left-medium" class="uk-padding-large uk-padding-remove-horizontal uk-padding-remove-top">
						<!-- Falta foto -->
						<img src="../assets/images/novia1.jpg" :alt="novia.nombre" class="uk-border-circle uk-width-medium@l uk-width-large uk-box-shadow-large uk-width-small">
						<div class="uk-padding-small uk-padding-remove-bottom">
							<h1 class="uk-h2">{{ novia.nombre }}</h1>
							<p class="text-deskripsi uk-width-large@l uk-width-xxlarge uk-text-justify uk-margin-auto-right uk-margin-auto-left">{{ novia.datos }}</p>
						</div>
					</div>
					<!-- Novio -->
					<div uk-scrollspy="cls:uk-animation-slide-right-medium" class="uk-padding-large uk-padding-remove-horizontal  uk-padding-remove-bottom@m uk-padding-remove-bottom@s uk-padding-remove-bottom@xs uk-padding-remove-top">
						<!-- Falta foto -->
						<img src="../assets/images/novio1.jpg" :alt="novio.nombre" class="uk-border-circle uk-width-medium@l uk-width-large uk-box-shadow-large">
						<div class="uk-padding-small uk-padding-remove-bottom">
							<h1 class="uk-h2">{{ novio.nombre }}</h1>
							<p class="text-deskripsi uk-width-large@l uk-width-xxlarge uk-text-justify uk-margin-auto-right uk-margin-auto-left">{{ novio.datos }}</p>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {
  name: 'Profile',

  data () {
	return { novia: { nombre: 'Damaris', datos: 'hola soy Damaris' }, 
	novio: { nombre: 'Omar', datos: 'Hola soy Omar, Originario de Guadalajara, Estoy listo.' } }
  }
}
</script>

<style lang="css" scoped>
	#profile {
		padding-top: 1px;
        background-color: #c1ebf7;
	}
    .text-deskripsi {
    	color: #666666 !important;
    }

	@media screen and (max-width: 1024px) {
		
	}
</style>