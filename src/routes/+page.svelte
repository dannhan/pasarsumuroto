<script>
	import Card from './Card.svelte';
	import Products from './Products.svelte';
</script>

<section class="bg-[#d0e6ec] px-6">
	<div class="relative mx-auto flex max-w-screen-2xl">
		<div class="py-24">
			<h2 class="mb-10 text-4xl font-bold">Selamat Datang di Laman Resmi</h2>
			<span class="mb-10 block space-y-4 text-6xl font-extrabold">
				<h1>Pasar Sumoroto</h1>
				<h1>Kabupaten Ponorogo</h1>
			</span>
			<p class="dapatkan-kebutuhan-anda mb-10">
				Dapatkan Kebutuhan Anda di Pasar Sumoroto dengan Mudah, Murah, dan Cepat.
			</p>
			<div class="ms-3 flex">
				<img class="more-vendors-group-child" loading="eager" alt="" src="/assets/group-1.svg" />

				<div class="dengan-lebih-dari-container">
					<span>dengan Lebih dari</span>
					<span class="span"> 239 </span>
					<span>Pilihan Pedagang</span>
				</div>
			</div>
		</div>

		<img
			id="baju"
			class="absolute right-32 top-10 z-10 h-[500px] w-[500px]"
			alt=""
			src="/assets/product-categories@2x.png"
		/>
		<img
			id="pembayaran"
			class="absolute right-0 top-8 h-[260px] w-[260px]"
			loading="eager"
			alt=""
			src="/assets/ellipse-5@2x.png"
		/>
		<img
			id="keranjang"
			class="absolute right-28 top-60 z-20 h-[210px] w-[210px]"
			alt=""
			src="/assets/ellipse-6@2x.png"
		/>
		<img
			id="uang"
			class="absolute right-[440px] top-[356px] z-30 h-[64px] w-[64px]"
			loading="eager"
			alt=""
			src="/assets/ellipse-4@2x.png"
		/>
	</div>
</section>

<section class="mx-auto flex max-w-screen-2xl justify-between px-16 py-12">
	<Card class="text-3xl font-extrabold uppercase text-red-600">
		<div>
			<h1>Lebih</h1>
			<h1>Dari</h1>
		</div>

		<div>
			<img alt="239" src="/assets/pedagang-more@2x.png" class="w-28" />
		</div>

		<div>
			<h1>Pilihan</h1>
			<h1>Pedagang</h1>
		</div>
	</Card>

	<Card class="mt-8 text-3xl font-extrabold uppercase text-[#1281A1]">
		<div>
			<h1>Tawar</h1>
			<h1>Untuk</h1>
		</div>

		<div>
			<img alt="239" src="/assets/rectangle-7209-1@2x.png" class="h-[88px]" />
		</div>

		<div>
			<h2 class="text-base">Mendapatkan</h2>
			<h1>Harga</h1>
			<h1>Terbaik</h1>
		</div>
	</Card>

	<Card class="text-3xl font-extrabold uppercase text-[#1281A1]">
		<div>
			<h1>Jendela</h1>
		</div>

		<div>
			<img alt="239" src="/assets/homepage-container@2x.png" class="h-[88px]" />
		</div>

		<div>
			<h1>Budaya</h1>
			<h1>Lokal</h1>
		</div>
	</Card>

	<Card class="mt-8 text-3xl font-extrabold uppercase text-[#1281A1]">
		<div>
			<h1>Dukung</h1>
		</div>

		<div>
			<img alt="239" src="/assets/rectangle-7209-1@2x.png" class="h-[88px]" />
		</div>

		<div>
			<h1>Ekonomi</h1>
			<h1>Kerakyatan</h1>
		</div>
	</Card>
</section>

<div id="separator" class="mx-auto h-2 max-w-screen-2xl rounded-xl bg-indigo-50" />

<Products />

<div id="separator" class="mx-auto h-2 max-w-screen-2xl rounded-xl bg-indigo-50" />

<section class="mx-auto grid max-w-screen-2xl py-12">
	<div class="flex justify-between">
		<div class="text-2xl font-extrabold">
			<h1>Lokasi</h1>
			<h1 class="text-[#1281A1]">Pasar Rakyat</h1>
			<h1 class="text-[#FF6B00]">Sumuroto</h1>
		</div>

		<div>
			<p class="w-[400px]">
				Berikut adalah lokasi Pasar Sumoroto Kabupaten Ponorogoyang ditampilkan dalam titik poin di
				Peta Indonesia. Untuk melihat detail lokasi Pasar Sumoroto maka klik tanda yang ada di peta.
			</p>
		</div>
	</div>

	<a href="https://maps.app.goo.gl/zHJRqNQKXXVvp5Sb6" class="mt-10">
		<img loading="eager" alt="" src="/assets/rectangle-46@2x.png" />
	</a>
</section>

<div id="separator" class="mx-auto h-2 max-w-screen-2xl rounded-xl bg-indigo-50" />

<section class="body-5-fix py-6">
	<h1 class="text-center text-4xl font-extrabold">
		<span class="kisaran-harga-bahan">Informasi</span>
		<span class="text-[#FF6B00]">Kisaran Harga Bahan Pokok</span>
	</h1>

	<div class="mx-auto mt-10 flex w-fit justify-between gap-36 rounded-3xl bg-[#D0E6EC] px-12 py-6">
		<div class="flex flex-col text-3xl font-bold">
			<i>dapat dilihat melalui </i>
			<i>laman web berikut</i>
			<i class="text-[#FF6B00] underline">siskaperbapo.jatimprov.go.id</i>
			<i>atau pindai kode QR di samping</i>
		</div>

		<!-- <img class="body-5-fix-child" alt="" src="/assets/vector-1.svg" /> -->
		<!-- <img class="image-background-remover" loading="eager" alt="" src="/assets/vector-2.svg" /> -->

		<img class="w-[150px]" loading="eager" alt="" src="/assets/imageremovebgpreview-1-1@2x.png" />
	</div>
</section>

<footer class="my-6">
	<div class="flex justify-center gap-4">
		<div class="flex w-fit justify-between divide-x divide-solid divide-black">
			<a href="/">
				<img
					class="mr-4 h-16"
					loading="eager"
					alt="Lambang Ponorogo"
					src="/assets/lambang-kabupaten-ponorogo-1969-1@2x.png"
				/>
			</a>
			<a href="/">
				<img
					class="ml-4 h-16"
					loading="eager"
					alt="Logo Pasar Rakyat"
					src="/assets/logotext-1@2x.png"
				/>
			</a>
		</div>
		<span class="flex flex-col justify-center opacity-50">
			<h2 class="text-[18px] font-extrabold leading-none">Pasar Rakyat</h2>
			<h1 class="text-[24px] font-extrabold leading-none">Sumuroto</h1>
		</span>
	</div>
</footer>

