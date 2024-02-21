<script>
	import Separator from '$lib/Separator.svelte';
	import Banner from './(components)/Banner.svelte';
	import List from './(components)/List.svelte';
	import Products from './(components)/Products.svelte';
	import Location from './(components)/Location.svelte';
	import Information from './(components)/Information.svelte';
</script>

<svelte:head>
	<title>Pasar Sumoroto</title>
	<meta name="description" content="Pasar Sumoroto Landing Page" />
</svelte:head>

<main>
	<Banner />

	<article class="mx-[100px] max-w-[1240px] space-y-12 py-12 min-[1440px]:mx-auto">
		<List class="flex justify-between px-10" />
		<Separator />
		<Products class="grid text-center" />
		<Separator />
		<Location class="space-y-6" />
		<Separator />
		<Information class="flex flex-col items-center" />
	</article>
</main>
