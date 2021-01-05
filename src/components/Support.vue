<template>
	<div id="support">
		<!-- <h1 class="uk-heading-line uk-text-center uk-h1 uk-padding-small title" uk-scrollspy="cls:uk-animation-slide-top-small"><span>Supported</span></h1> -->
	

			<p class="copyright">ralo44 &copy; 2020</p>
	</div>
</template>

<script>
export default {

  name: 'Support',
}
</script>

<style lang="css" scoped>
	#support {
        background-color: #c1ebf7;
    } 
    .wrapper {
    	padding-bottom: 5px;
    }
    .copyright {
    	font-weight: bold;
    }

	@media screen and (max-width: 1024px) {
		li {
			font-size: 14px;
			margin-left: 15px;
			margin-right: 15px;
		}
	}
</style>