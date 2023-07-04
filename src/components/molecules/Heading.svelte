<script>
	import Subtitle from '../atoms/typography/Subtitle.svelte';
	import Title from '../atoms/typography/Title.svelte';

	export let title;
	export let subtitle = undefined;
</script>

<div class="flex flex-col gap-4 justify-between items-center md:flex-row lg:gap-6">
	<div class="md:w-3/6">
		<Title>{title}</Title>
	</div>
	{#if subtitle}
		<div class="md:w-3/6 md:text-right">
			<Subtitle>{subtitle}</Subtitle>
		</div>
	{/if}
</div>
