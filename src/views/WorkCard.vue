<template>
	<div class="workspace">
		<img :src="imgMamikos">
		<img :src="imgShipping">
		<img :src="imgTravelling">
	</div>
</template>

<script>
export default {

  name: 'WorkCard',

  data () {
    return {
    	imgMamikos: '../assets/web-mamikos.png',
    	imgShipping: '../assets/web-shipping.png',
    	imgTravelling: '../assets/web-travelling.png'
    }
  }
}
</script>

<style lang="css" scoped>
</style>