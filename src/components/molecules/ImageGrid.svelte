<script>
	import { onDestroy } from 'svelte';
	import GradientImage from './GradientImage.svelte';
	import { createMediaStore } from 'svelte-media-queries';

	const isMobile = createMediaStore('(max-width: 768px)');
	onDestroy(() => isMobile.destroy());
</script>

<div class="grid grid-cols-2 gap-6 md:grid-cols-3 lg:gap-10">
	<GradientImage
		src="/img/spbu.webp"
		alt="SPBU Jelekong"
		roundedPosition="tl"
		className="aspect-square"
	/>
	<GradientImage
		src="/img/smkn-7-baleendah.webp"
		alt="SMKN 7 Baleendah"
		roundedPosition={$isMobile ? 'tr' : 'none'}
		className="aspect-square"
	/>
	<GradientImage
		src="/img/grand-al-ihsan.webp"
		alt="Grand Al Ihsan Residence"
		roundedPosition={$isMobile ? 'none' : 'tr'}
		className="aspect-square"
	/>
	<GradientImage
		src="/img/fitrah-insani-2.webp"
		alt="SD & SMP IT Fitrah Insani 2"
		roundedPosition={$isMobile ? 'none' : 'bl'}
		className="aspect-square"
	/>
	<GradientImage
		src="/img/perumahan-bumi-siliwangi.webp"
		alt="Perumahan Bumi Siliwangi"
		roundedPosition={$isMobile ? 'bl' : 'none'}
		className="aspect-square"
	/>
	<GradientImage
		src="/img/modif-resto.webp"
		alt="Modif Resto"
		roundedPosition="br"
		className="aspect-square"
	/>
</div>
