<script>
	import clsx from 'clsx';
	import Brand from '../molecules/Brand.svelte';
	import DesktopNavbar from '../molecules/Navbar/Desktop.svelte';
	import MobileNavbar from '../molecules/Navbar/Mobile.svelte';

	let scrollY;
</script>

<svelte:window bind:scrollY />

<header
	class={clsx(
		'transition-shadow fixed inset-x-0 top-0 bg-white/85 z-[100] backdrop-blur',
		scrollY > 30 && 'shadow'
	)}
>
	<div
		class="container flex justify-between items-center py-4 px-8 mx-auto md:py-8 md:px-0 lg:px-32"
	>
		<Brand />
		<div class="hidden md:block">
			<DesktopNavbar />
		</div>
		<MobileNavbar />
	</div>
</header>
