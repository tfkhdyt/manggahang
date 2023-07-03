<script>
	import GradientImage from '../GradientImage/GradientImage.svelte';
</script>

<div class="pl-8 space-y-4 w-1/2">
	<GradientImage
		src="/img/gunung-geulis.jpg"
		alt="Gunung geulis"
		roundedPosition="t"
		className="aspect-[3/1]"
	/>
	<GradientImage src="/img/lapang-carik.jpg" alt="Lapangan Carik" className="aspect-[2.5/1]" />
	<GradientImage
		src="/img/kantor-kelurahan.jpg"
		alt="Kantor kelurahan"
		roundedPosition="b"
		className="aspect-[4/3]"
	/>
</div>
