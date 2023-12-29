<template>
	<div>
		<header class="shadow-sm bg-white">
			<nav class="container mx-auto p-4">
				<NuxtLink
					class="font-bold"
					to="/products"
				>
					My Store | Merch
				</NuxtLink>
			</nav>
		</header>
	</div>

	<div class="container mx-auto p-4">
		<slot />
	</div>

	<footer
		class="container mx-auto p-4 border-t border-solid border-slate-900/20"
	>
		<ul class="flex items-center justify-center gap-5">
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
