<template>
	<div>
		<p class="big-word">
			{{ textTitle }}
		</p>
		<span class="subtitle">{{ textSubtitle }}</span>
	</div>
</template>

<script>
export default {
  name: 'BigWord',

  props: {
  	textTitle: {
  		required: true,
  		type: String
  	},
  	textSubtitle: {
  		required: true,
  		type: String
  	}
  }

}
</script>

<style lang="css" scoped>
	.big-word {
		font-size: 60px;
		font-weight: bold;
		text-transform: uppercase;
		margin: 0;
		line-height: 1;
	}

	.subtitle {
		font-size: 20px;
		font-weight: 300;
		margin: 8px 0 8px  0px;
		display: inline-block;
	}
</style>