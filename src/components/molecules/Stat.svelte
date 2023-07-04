<script>
	import MediumText from '../atoms/typography/MediumText.svelte';
	import NormalText from '../atoms/typography/NormalText.svelte';

	export let title;
	export let value;
</script>

<div
	class="p-7 space-y-3 transition md:p-10 lg:space-y-6 rounded-[2rem] bg-neutral-100 hover:bg-neutral-200"
>
	<MediumText>{value}</MediumText>
	<NormalText>{title}</NormalText>
</div>
