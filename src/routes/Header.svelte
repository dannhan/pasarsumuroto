<script>
	import HeaderLogo from './HeaderLogo.svelte';
</script>

<header class={$$restProps.class}>
	<nav class="mx-auto flex max-w-[1240px] items-center justify-between gap-16">
		<span class="flex items-center gap-4">
			<HeaderLogo class="flex gap-4" />

			<ul class="flex flex-row items-center gap-4 text-xl font-extrabold">
				<li>
					<a href="/">Profil Pasar</a>
				</li>
				<li>
					<a href="/">Kontak Kami</a>
				</li>
				<li>
					<a href="/">Pelaporan dan Perijinan</a>
				</li>
			</ul>
		</span>

		<form class="xl:flex grow border-collapse justify-end hidden">
			<label for="default-search" class="sr-only">Search</label>

			<input
				type="search"
				id="default-search"
				class="block max-w-96 grow rounded-l-full border border-gray-300 px-6 py-2 text-sm"
				placeholder="cari produk atau layanan"
				required
			/>
			<button class="flex items-center rounded-r-full border border-gray-300 bg-gray-200 pl-4 pr-6">
				<svg
					class="h-4 w-4 text-gray-500 dark:text-gray-400"
					aria-hidden="true"
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 20 20"
				>
					<path
						stroke="currentColor"
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="m19 19-4-4m0-7A7 7 0 1 1 1 8a7 7 0 0 1 14 0Z"
					/>
				</svg>
			</button>
		</form>
	</nav>
</header>
