<script>
	export let header;
	export let image;
	export let footer;
	export let color;
	export let isShifted = false;
</script>

<!-- eslint-disable svelte/no-at-html-tags -->
<div
	class="flex h-[303px] w-[215px] flex-col items-center justify-between rounded-xl bg-gradient-to-br from-indigo-50 to-indigo-100 py-4 text-center shadow-inner {color}"
	class:mt-7={isShifted}
>
	<h1 class="text-3xl font-extrabold uppercase leading-none">
		{#each header.split('_') as head}
			{@html head}<br />
		{/each}
	</h1>

	<img alt="list" src="/assets/{image}.png" class="h-[95px] w-[101px]" />

	<h1 class="text-3xl font-extrabold uppercase leading-none">
		{#each footer.split('_') as foot}
			{@html foot}<br />
		{/each}
	</h1>
</div>

<style>
	div {
		box-shadow:
			inset -3px -3px 8px -3px rgba(0, 0, 0, 0.1),
			-7px 0px 10px -3px #eaf0ff;
	}
</style>
