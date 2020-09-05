<template>
	<section class="contact">
		<div class="col col-1">
			<big-word
				text-title="Contact"
				text-subtitle=" Wanna talk bout web programming, javascript, or video games? Hit me up!"
			></big-word>

			<div class="contact-info">	
				<p>Reach me at:</p>
				<p>a.yulian.h@gmail.com</p>
				<p>+62 812 2013 808</p>
				<p>
					<a 
						href="https://www.linkedin.com/in/anom-yulian-265024145/" 
						target="_blank"
					>
						Linkedin
					</a> |
					<a 
						href="https://www.facebook.com/croki11/"
						target="_blank"
					>
						Facebook
					</a>
				</p>
			</div>
		</div>
		
	</section>
</template>

<script>
import BigWord from '@/components/BigWord.vue'
	
	export default {
		name: 'ContactCard',
		components: {
			BigWord
		}
	}
</script>

<style lang="scss" scoped>

.col {
	width: 420px;
}

.contact-info {
	margin-top: 20px;
	p {
    font-size: 14px;
    line-height: 2;
    margin: 8px 0;
	}
	a {
		text-decoration: none;
		color: inherit;
	}
} 
</style>