<script setup>
	definePageMeta({
		layout: "products",
	});

	const { data: products } = await useFetch(
		"https://fakestoreapi.com/products"
	);
</script>

<template>
	<div>
		<div class="container px-10 grid grid-cols-4 gap-5">
			<div
				v-for="product in products"
				:key="product.id"
			>
				<NuxtLink :to="`/products/${product.id}`">
					<NuxtImg
						width="200"
						loading="lazy"
						sizes="200px sm:100px md:300 lg:400px"
						:src="`${product.image}`"
					/>
				</NuxtLink>
				<p>{{ product.title }}</p>
				<p>$ {{ product.price }}</p>
			</div>
		</div>
	</div>
</template>
