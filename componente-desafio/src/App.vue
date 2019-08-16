<template>
	<v-app>
		<Menu />
		<Titulo />
		<Carousel />
		<Footer />
	</v-app>
</template>

<script>
import Menu from '@/components/template/App-menu.vue'
import Titulo from '@/components/template/App-titulo.vue'
import Carousel from '@/components/widgets/App-carousel.vue'
import Footer from '@/components/template/App-footer.vue'

export default {
	components: {
		Menu,
		Titulo,
		Carousel,
		Footer
	}
	
}
</script>
