<template>
	<div>
		<header>
			<nav>
				<NuxtLink to="/products">My Store | Merch</NuxtLink>
			</nav>
		</header>
	</div>

	<div>
		<slot />
	</div>

	<footer>
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
	</footer>
</template>

<style lang="scss" scoped>
	.router-link-active {
		color: rgb(91, 179, 150);
	}
</style>
