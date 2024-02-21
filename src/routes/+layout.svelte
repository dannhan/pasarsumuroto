<script>
	import '../app.pcss';
	import '@fontsource-variable/plus-jakarta-sans';
	import Header from './Header.svelte';
</script>

<Header class="sticky top-0 z-50 bg-white px-[100px] py-6" />
<slot />

<style>
	:global(body) {
		font-family: 'Plus Jakarta Sans Variable', sans-serif;
	}
</style>
