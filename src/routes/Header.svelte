<script>
	import HeaderLogo from './HeaderLogo.svelte';
	import HeaderLinks from './HeaderLinks.svelte';
	import HeaderSearchInput from './HeaderSearchInput.svelte';
</script>

<header>
	<nav class="px-[100px] py-6">
		<div class="mx-auto flex max-w-screen-2xl flex-wrap items-center justify-between">
			<div class="flex items-center gap-4">
				<HeaderLogo class="flex gap-4" />
				<HeaderLinks class="flex flex-row items-center gap-4 text-xl font-extrabold" />
			</div>

			<HeaderSearchInput class="flex grow justify-end border-collapse" />
		</div>
	</nav>
</header>
