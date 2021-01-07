<script>
	import Tailwindcss from './Tailwind.svelte';

	export let name;
</script>
<Tailwindcss />
<main>
	<div class="w-screen h-screen bg-gray-800">
		<h1 class="text-white">Hello {name}!</h1>
		<p class="text-white">Visit the <a class="text-blue-200 underline" href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
	</div>
</main>