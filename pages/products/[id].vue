<script setup>
	const { id } = useRoute().params;
</script>

<template>
	<div>
		<h3>Product Details for {{ id }}</h3>
		<p>
			Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quam quia
			voluptate modi culpa maxime optio nesciunt sunt, expedita veniam assumenda
			impedit delectus quo inventore, est amet porro veritatis ut accusamus?
		</p>
	</div>
</template>

<style lang="scss" scoped>
	h3 {
		margin-bottom: 20px;
		font-size: 36px;
	}

	p {
		margin: 20px 0;
	}
</style>
