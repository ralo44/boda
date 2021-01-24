<template>
	<div id="support">	
			<p class="copyright">ralo44 &copy; 2021</p>
	</div>
</template>

<script>
export default {

  name: 'Support',
}
</script>

<style lang="css" scoped>
	#support {
        background-color: #a17188;
		color: white;
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