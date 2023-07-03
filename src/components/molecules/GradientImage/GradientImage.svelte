<script>
	import GradientOverlay from '../../atoms/GradientOverlay.svelte';
	import RoundedImage from '../../atoms/images/RoundedImage.svelte';

	export let roundedPosition = '';
	export let aspectRatio;
	export let src;
	export let alt;
</script>

<div class="relative ml-auto w-5/6 group" title={alt}>
	<GradientOverlay {roundedPosition} {aspectRatio} />
	<RoundedImage {src} {alt} {roundedPosition} {aspectRatio} />
</div>
