<template>
	<header class="section_header">
		<img src="../assets/31530356_bird_2.svg" alt="" class="logo_header" />
		<nav>
			<RouterLink to="/">Autres</RouterLink>
			<RouterLink to="/about">About</RouterLink>
			<RouterLink to="/portfolio">Home</RouterLink>
		</nav>
	</header>
</template>

<script lang="ts" setup></script>

<style lang="scss" scoped>
.section_header {
	display: flex;
	justify-content: center;
	flex-direction: column;
	.logo_header {
		max-width: 6rem;
		align-items: center;
	}
	nav {
		display: flex;
		gap: 1rem;
	}
}
</style>
