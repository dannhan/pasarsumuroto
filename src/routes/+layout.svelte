<script>
	import '../app.pcss';
	import '@fontsource-variable/plus-jakarta-sans';
  import Header from "./Header.svelte";
</script>

<Header />
<slot />

<style>
	:global(body) {
		font-family: 'Plus Jakarta Sans Variable', sans-serif;
	}
</style>
