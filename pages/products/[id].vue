<script setup>
	const { id } = useRoute().params;
	const uri = `https://fakestoreapi.com/products/${id}`;
	const { data: product } = await useFetch(uri);

	definePageMeta({
		layout: "products",
	});
</script>

<template>
	<div class="flex h-screen py-3 gap-10 justify-center">
		<NuxtImg
			width="400"
			loading="lazy"
			:src="`${product.image}`"
		/>
		<div>
			<p>{{ product.title }}</p>
			<p>$ {{ product.price }}</p>
		</div>
	</div>
</template>
