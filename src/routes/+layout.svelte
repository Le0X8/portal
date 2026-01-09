<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<div class="min-h-screen bg-white text-black dark:bg-black dark:text-white">
	<nav class="mx-auto flex w-full max-w-240 items-center p-4">
		<div class="basis-1/6 text-center">
			<a href="/">Savegames</a>
		</div>
		<div class="basis-1/6 text-center">
			<a href="https://store.steampowered.com/app/400/">Get Portal</a>
		</div>

		<div class="flex basis-2/6 items-center justify-center gap-2 text-2xl font-bold uppercase">
			<img src="/aperture.svg" alt="" class="h-6" />
			<a href="/">Aperture Science</a>
		</div>

		<div class="basis-1/6 text-center">
			<a href="https://store.steampowered.com/app/620/">Get Portal 2</a>
		</div>
		<div class="basis-1/6 text-center">
			<a href="https://github.com/Le0X8/portal">GitHub</a>
		</div>
	</nav>

	<main
		class="mx-auto prose min-h-[calc(100vh-2rem)] max-w-240 p-4 prose-neutral dark:prose-invert"
	>
		{@render children()}
	</main>

	<footer
		class="mx-auto mt-1 max-w-240 border-t border-neutral-300 py-2 text-center dark:border-neutral-700"
	>
		<p class="mb-1 text-sm">
			created by <a href="https://lesinski.cc/" class="underline">@Le0_X8</a>
		</p>
		<p class="text-xs">This is a fan-made project and not affiliated with Valve Corporation.</p>
	</footer>
</div>
