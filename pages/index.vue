<script setup></script>

<template>
	<div>
		<header>
			<nav>
				<NuxtLink to="/">My Store</NuxtLink>

				<ul>
					<li>
						<NuxtLink to="/">Home</NuxtLink>
					</li>

					<li>
						<NuxtLink to="/about">About</NuxtLink>
					</li>

					<li>
						<NuxtLink to="/products">Products</NuxtLink>
					</li>
				</ul>
			</nav>
		</header>

		<h2>Home</h2>

		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. In, optio. Eum,
			nobis, cum expedita ullam ipsa accusamus ipsum dolore quidem odit pariatur
			mollitia sit. Reprehenderit inventore qui natus repudiandae delectus.
		</p>

		<p>
			Lorem ipsum dolor sit amet consectetur adipisicing elit. In, optio. Eum,
			nobis, cum expedita ullam ipsa accusamus ipsum dolore quidem odit pariatur
			mollitia sit. Reprehenderit inventore qui natus repudiandae delectus.
		</p>
	</div>
</template>

<style lang="scss" scoped>
	h2 {
		margin-bottom: 20px;
		font-size: 36px;
	}

	p {
		margin: 20px 0;
	}
</style>
