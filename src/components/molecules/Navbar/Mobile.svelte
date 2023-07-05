<script>
	import { Hamburger } from 'svelte-hamburgers';
	import { fly } from 'svelte/transition';

	import DesktopNavbar from './Desktop.svelte';

	let open = false;
</script>

<div class="relative md:hidden">
	<Hamburger bind:open type="spring-r" --layer-height="3px" />
	{#if open}
		<div
			class="absolute right-0 py-4 px-6 bg-white rounded-lg shadow w-42 top-15"
			transition:fly={{ y: -25, duration: 250 }}
		>
			<DesktopNavbar className="flex flex-col gap-6 md:flex-row md:gap-0" />
		</div>
	{/if}
</div>
