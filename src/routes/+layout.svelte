<script>
	import '@fontsource-variable/plus-jakarta-sans';
	import '../app.pcss';
	import Header from './Header.svelte';
	import Footer from './Footer.svelte';
</script>

<Header class="sticky top-0 z-50 bg-white px-[100px] py-6" />
<slot />
<Footer class="my-6 flex" />

<style>
	:global(body) {
		font-family: 'Plus Jakarta Sans Variable', sans-serif;
	}
</style>
