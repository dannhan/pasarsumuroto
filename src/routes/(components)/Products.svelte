<script>
	import Card from './Card.svelte';
</script>

<section class="flex justify-between py-20">
	<Card class="text-3xl font-extrabold uppercase text-red-600">
		<h1>Lebih<br />Dari</h1>
		<img alt="239" src="/assets/pedagang-more@2x.png" class="w-28" />
		<h1>Pilihan<br />Pedagang</h1>
	</Card>

	<Card class="mt-8 text-3xl font-extrabold uppercase text-[#1281A1]">
		<h1>Tawar<br />Untuk</h1>
		<img alt="239" src="/assets/rectangle-7209-1@2x.png" class="h-[88px]" />
		<h1><span class="text-base">Mendapatkan</span> Harga Terbaik</h1>
	</Card>

	<Card class="text-3xl font-extrabold uppercase text-[#009943]">
		<h1>Jendela</h1>
		<img alt="239" src="/assets/homepage-container@2x.png" class="h-[88px]" />
		<h1>Budaya<br />Lokal</h1>
	</Card>

	<Card class="mt-8 text-3xl font-extrabold uppercase text-[#FF6B00]">
		<h1>Dukung</h1>
		<img alt="239" src="/assets/rectangle-7209@2x.png" class="h-[88px]" />
		<h1>Ekonomi<br />Kerakyatan</h1>
	</Card>
</section>

<div id="separator" class="h-2 rounded-xl bg-indigo-50" />

<section class="grid py-12 text-center">
	<h1 class="text-3xl font-extrabold">Produk</h1>
	<h1 class="text-3xl font-extrabold">Pasar Sumuroto</h1>

	<div class="grid grid-cols-4 gap-4">
		<div class="flex flex-col items-center">
			<img alt="" src="/assets/sembako@2x.png" class="h-[250px] w-[295px]" />
			<h1 class="text-2xl font-extrabold">Sembako</h1>
		</div>

		<div class="flex flex-col items-center">
			<img alt="" src="/assets/rectangle-15@2x.png" class="h-[250px] w-[295px]" />
			<h1 class="text-2xl font-extrabold">Sayur Mayur</h1>
		</div>

		<div class="flex flex-col items-center">
			<img alt="" src="/assets/rectangle-22@2x.png" class="h-[250px] w-[295px]" />
			<h1 class="text-2xl font-extrabold">Daging</h1>
		</div>

		<div class="flex flex-col items-center">
			<img alt="" src="/assets/rectangle-23@2x.png" class="h-[250px] w-[295px]" />
			<h1 class="text-2xl font-extrabold">Telur</h1>
		</div>

		<div class="flex flex-col items-center">
			<img loading="eager" alt="" src="/assets/rectangle-21@2x.png" class="h-[250px] w-[295px]" />
			<h1 class="text-2xl font-extrabold">Aneka Jajanan</h1>
		</div>

		<div class="flex flex-col items-center">
			<img alt="" src="/assets/rectangle-21-1@2x.png" class="h-[250px] w-[295px]" />
			<h1 class="text-2xl font-extrabold">Makanan Ringan</h1>
		</div>

		<div class="flex flex-col items-center">
			<img alt="" src="/assets/rectangle-21-2@2x.png" class="h-[250px] w-[295px]" />
			<h1 class="text-2xl font-extrabold">Pakaian</h1>
		</div>

		<div class="flex flex-col items-center">
			<img alt="" src="/assets/rectangle-21-3@2x.png" class="h-[250px] w-[295px]" />
			<h1 class="text-2xl font-extrabold">Kebutuhan Rumah</h1>
		</div>
	</div>
</section>

<div id="separator" class="h-2 rounded-xl bg-indigo-50" />