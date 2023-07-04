<script>
	import Brand from '../molecules/Brand.svelte';
	import DesktopNavbar from '../molecules/Navbar/Desktop.svelte';
	import MobileNavbar from '../molecules/Navbar/Mobile.svelte';
</script>

<header id="home">
	<div
		class="container flex justify-between items-center py-6 px-8 mx-auto md:py-8 md:px-0 lg:px-32"
	>
		<Brand />
		<div class="hidden md:block">
			<DesktopNavbar />
		</div>
		<MobileNavbar />
	</div>
</header>
