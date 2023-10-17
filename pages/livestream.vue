<template>
	<Navbar />
	<section class="livestream-container">
		<h2>Welcome to the Rogue Revolution</h2>
		<iframe
			src="https://explore.org/livecams/african-wildlife/african-animal"
			frameborder="0"
			width="800"
			height="550"
			allowfullscreen
			class="livestream"
		></iframe>
	</section>
	<Footer />
</template>

<style scoped>
.livestream-container {
	min-height: 500px;
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
	margin: 1em;
}

.livestream {
	margin: 2em 0;
}
</style>
