<script>
	import MediumText from '../../atoms/typography/MediumText.svelte';
	import NormalText from '../../atoms/typography/NormalText.svelte';

	export let title;
	export let value;
</script>

<div class="p-10 space-y-6 transition rounded-[2rem] bg-neutral-100 hover:bg-neutral-200">
	<MediumText>{value}</MediumText>
	<NormalText>{title}</NormalText>
</div>
