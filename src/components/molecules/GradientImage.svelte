<script>
	import GradientOverlay from '../atoms/GradientOverlay.svelte';
	import RoundedImage from '../atoms/images/RoundedImage.svelte';

	export let roundedPosition = 'none';
	export let className = '';
	export let src;
	export let alt;
</script>

<div class="relative group" title={alt}>
	<GradientOverlay {roundedPosition} {className} />
	<RoundedImage {src} {alt} {roundedPosition} {className} />
</div>
