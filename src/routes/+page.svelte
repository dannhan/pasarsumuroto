<script>
	import Banner from './(components)/Banner.svelte';
	import Products from './(components)/Products.svelte';
	import Footer from './(components)/Footer.svelte';
</script>

<main>
	<Banner />

	<!-- Main Content -->
	<div id="main-content" class="mx-[100px] max-w-screen-2xl">
		<Products />

		<section class="grid py-12">
			<div class="flex justify-between">
				<!-- <h1>Lokasi</h1>
					<h1 class="text-[#1281A1]">Pasar Rakyat</h1>
					<h1 class="text-[#FF6B00]">Sumuroto</h1> -->
				<h1 class="text-4xl font-extrabold">
					Lokasi <br />
					<span class="text-[#1281A1]">Pasar Rakyat</span><br />
					<span class="text-[#FF6B00]">Sumuroto</span>
				</h1>

				<p class="w-[500px] text-[20px] leading-7">
					Berikut adalah lokasi Pasar Sumoroto Kabupaten Ponorogo yang ditampilkan dalam titik poin
					di Peta Indonesia. Untuk melihat detail lokasi Pasar Sumoroto maka klik tanda yang ada di
					peta.
				</p>
			</div>

			<a href="https://maps.app.goo.gl/zHJRqNQKXXVvp5Sb6" class="mt-10">
				<img loading="eager" alt="" src="/assets/rectangle-46@2x.png" />
			</a>
		</section>

		<div id="separator" class="mx-auto h-2 max-w-screen-2xl rounded-xl bg-indigo-50" />

		<section class="flex flex-col items-center py-12">
			<h1 class="text-4xl font-extrabold">
				<span class="kisaran-harga-bahan">Informasi</span>
				<span class="text-[#FF6B00]">Kisaran Harga Bahan Pokok</span>
			</h1>

			<div class="mt-4 flex justify-between gap-36 rounded-3xl bg-[#D0E6EC] px-12 py-6">
				<div class="flex flex-col text-3xl font-bold">
					<i>dapat dilihat melalui </i>
					<i>laman web berikut</i>
					<i class="text-[#FF6B00] underline">siskaperbapo.jatimprov.go.id</i>
					<i>atau pindai kode QR di samping</i>
				</div>

				<!-- <img class="body-5-fix-child" alt="" src="/assets/vector-1.svg" /> -->
				<!-- <img class="image-background-remover" loading="eager" alt="" src="/assets/vector-2.svg" /> -->

				<img
					class="w-[150px]"
					loading="eager"
					alt=""
					src="/assets/imageremovebgpreview-1-1@2x.png"
				/>
			</div>
		</section>

		<Footer />
	</div>
	<!-- End Main Content -->
</main>
