<template>
	<Navbar />
	<div class="hero-container">
		<img src="/hero.png" alt="rogue hero image" class="hero" />
		<p class="featured-text">FEATURED PRODUCTS</p>
		<img src="/featured.png" alt="featred projects" class="featured" />
	</div>
	<Footer />
</template>

<style>
* {
	margin: 0;
	padding: 0;
	text-decoration: none;
	box-sizing: border-box;
}

.hero-container {
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}

.featured-text {
	padding: 1em;
	color: black;
	font-weight: 900;
	align-self: self-start;
	margin-left: 14em;
	font-size: 1.5rem;
}

.hero {
	height: 45vh;
	cursor: pointer;
}

.featured {
	height: 25vh;
	cursor: pointer;
	padding-bottom: 2em;
}

@media (max-width: 1000px) {
	.hero {
		height: 290px;
		width: 100%;
	}

	.featured-text {
		align-self: center;
		margin-left: 0;
	}

	.featured {
		height: 200px;
		width: 100%;
	}
}
</style>
