<script>
	import Separator from '$lib/Separator.svelte';
	import Banner from './(components)/Banner.svelte';
	import List from './(components)/List.svelte';
	import Products from './(components)/Products.svelte';
	import Location from './(components)/Location.svelte';
	import Information from './(components)/Information.svelte';
	import Footer from './(components)/Footer.svelte';
</script>

<main>
	<Banner />

	<article class="mx-[100px] max-w-[1240px] space-y-12 py-12 min-[1440px]:mx-auto">
		<List class="flex justify-between" />
		<Separator />
		<Products class="grid text-center" />
		<Separator />
		<Location class="space-y-6" />
		<Separator />
		<Information class="flex flex-col items-center" />
	</article>

	<Footer />
</main>
