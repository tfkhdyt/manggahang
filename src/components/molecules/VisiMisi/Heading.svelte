<script>
	import Title from '../../atoms/typography/Title.svelte';
	import GradientImage from '../GradientImage.svelte';
</script>

<div class="flex flex-col gap-6 items-center md:flex-row md:gap-12">
	<div class="md:w-1/2">
		<GradientImage
			src="/img/manggahang-1.jpg"
			alt="SDN Manggahang 1"
			roundedPosition="tl"
			className="aspect-[2/1]"
		/>
	</div>
	<div class="md:w-1/2">
		<Title>Visi dan Misi Manggahang</Title>
	</div>
</div>
