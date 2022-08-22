<script>
import Footer from './components/Footer.vue'

export default {
	
}

</script>

<template>
	
	<header>
		My app!
	</header>
	
	<nav>
		<RouterLink to="/">Home</RouterLink>
		<RouterLink to="/about">About</RouterLink>
	</nav>
	
	<main>
		<RouterView></RouterView>
	</main>
	
	<Footer :copyrightYear="2022"></Footer>
	
</template>

<style scoped>

nav{
	background-color: yellow;
}

</style>
