<template>
	<div class="hero-section">
		<h1>Bienvenue sur Mon Portfolio</h1>
		<p>Découvrez mes projets et mes compétences.</p>
		<button>En savoir plus</button>
	</div>
</template>

<script lang="ts" setup></script>

<style scoped>
.hero-section {
	background-image: url("/path/to/your/image.jpg"); /* Remplacez par le chemin de votre image */
	background-size: cover;
	background-position: center;
	height: 500px;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	color: #fff;
	text-align: center;
}

.hero-section h1 {
	font-size: 2.5rem;
	margin-bottom: 20px;
}

.hero-section p {
	font-size: 1.2rem;
	margin-bottom: 20px;
}

.hero-section button {
	padding: 10px 20px;
	font-size: 1rem;
	color: #000;
	background-color: #fff;
	border: none;
	cursor: pointer;
	transition: background-color 0.3s ease;
}

.hero-section button:hover {
	background-color: #ccc;
}
</style>
