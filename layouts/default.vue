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
	</div>

	<div>
		<slot />
	</div>
</template>

<style lang="scss" scoped>
	.router-link-active {
		color: rgb(91, 179, 150);
	}
</style>
