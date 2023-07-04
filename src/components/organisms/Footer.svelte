<script>
	import Brand from '../molecules/Brand.svelte';
	import DesktopNavbar from '../molecules/Navbar/Desktop.svelte';
</script>

<footer class="bg-neutral-100">
	<div
		class="container py-12 px-8 mx-auto space-y-8 md:flex md:justify-between md:items-center md:px-0 md:space-y-0 lg:px-32"
	>
		<Brand />
		<div>
			<DesktopNavbar className="flex flex-col gap-6 md:flex-row md:gap-0" />
		</div>
	</div>
</footer>
