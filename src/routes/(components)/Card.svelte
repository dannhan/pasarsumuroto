<div
	class="flex h-80 w-56 flex-col items-center justify-between rounded-xl bg-gradient-to-br from-indigo-100 via-indigo-100 to-indigo-200 py-8 text-center shadow-inner {$$restProps.class}"
>
	<slot />
</div>

<style>
	div {
		box-shadow:
			inset -3px -3px 8px -3px rgba(0, 0, 0, 0.1),
			-7px 0px 10px -3px #eaf0ff;

	}
</style>
