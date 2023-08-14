<template>
	<div class="content">
		<TextIntroduction />
		<FormFreeTrial />
	</div>
</template>
<script setup>
	import { TextIntroduction, FormFreeTrial } from './components';
</script>

<style scoped>
	.content {
		display: flex;
		align-items: center;
		margin: 0 auto;
		max-width: 1400px;
		padding-top: 200px;
	}

	.content > div {
		flex: 0 1 50%;
	}

	@media (max-width: 1200px) {
		.content {
			padding-top: 80px;
			gap: 3rem;
			flex-direction: column;
		}
	}
</style>
