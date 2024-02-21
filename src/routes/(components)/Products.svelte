<section class={$$restProps.class}>
	<h1 class="text-4xl font-extrabold">Produk</h1>
	<h1 class="text-4xl font-extrabold">Pasar Sumuroto</h1>

	<div class="grid grid-cols-4 gap-4">
		{#each ['sembako', 'sayur-mayur', 'daging', 'telur', 'aneka-jajanan', 'makanan-ringan', 'pakaian', 'kebutuhan-rumah'] as src (src)}
			<div class="space-y-2">
				<div class="relative pb-[200px] xl:pb-[240px]">
					<img
						alt=""
						src="/assets/{src}.png"
						class="absolute left-1/2 h-full -translate-x-1/2 object-cover"
					/>
				</div>
				<h1 class="text-3xl font-extrabold capitalize">{src.split('-').join(' ')}</h1>
			</div>
		{/each}
	</div>
</section>
