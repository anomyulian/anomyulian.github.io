<template>
	<section class="home">
		<!-- card -->
		<big-word
			text-title="Anom Yulian"
			text-subtitle="Frontend Developer"
		></big-word>
		<p class="caption">
			A frontend developer with passion on design and other aesthetic stuff. Has three years experience on javascript, specifically on VueJs. Currently working and living in Semarang, Jawa Tengah.
		</p>

		<div class="contact">	
			<p>Reach me at:</p>
			<p>a.yulian.h@gmail.com</p>
			<p>+62 812 2013 808</p>
			<p>Linkedin</p>
		</div>
	</section>
</template>

<script>
// @ is an alias to /src
import BigWord from '@/components/BigWord.vue'

export default {
	name: 'Home',
	components: {
		BigWord,
	}
}
</script>


<style lang="scss" scoped>

.caption {
	margin-top: 30px;
	font-weight: 300;
	width: 60%;
}

.contact {
	margin-top: 80px;

	p {
		font-size: 12px;
		line-height: 1;
		margin: 8px 0;
	}
} 

</style>

