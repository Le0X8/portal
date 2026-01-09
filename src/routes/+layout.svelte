<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<div class="min-h-screen bg-white text-black dark:bg-black dark:text-white">
	<main
		class="mx-auto prose min-h-[calc(100vh-2rem)] max-w-240 p-4 prose-neutral dark:prose-invert"
	>
		{@render children()}
	</main>

	<footer
		class="mx-auto max-w-240 border-t border-neutral-300 pt-2 text-center dark:border-neutral-700"
	>
		<p class="text-sm">created by <a href="https://lesinski.cc/" class="underline">@Le0_X8</a></p>
	</footer>
</div>
