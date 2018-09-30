<template>
	<div class="links">
		<nuxt-link to="one">One</nuxt-link>
		<nuxt-link to="some/two">Two</nuxt-link>
		<nuxt-link to="some/three">Three</nuxt-link>
	</div>
</template>

<script>
export default {};
</script>

<style scoped>
.links {
	display: flex;
	justify-content: space-around;
}
</style>
