<script>
	import Subtitle from '../atoms/typography/Subtitle.svelte';
	import Title from '../atoms/typography/Title.svelte';

	export let title;
	export let subtitle = undefined;
</script>

<div class="flex justify-between items-center space-x-12 lg:space-x-4">
	<div class="w-3/6">
		<Title>{title}</Title>
	</div>
	{#if subtitle}
		<div class="w-3/6 text-right">
			<Subtitle>{subtitle}</Subtitle>
		</div>
	{/if}
</div>
