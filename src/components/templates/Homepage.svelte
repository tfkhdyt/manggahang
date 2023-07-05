<script>
	import Hero from '../organisms/Hero.svelte';
	import Header from '../organisms/Header.svelte';
	import TentangKami from '../organisms/TentangKami.svelte';
	import VisiMisi from '../organisms/VisiMisi.svelte';
	import Galeri from '../organisms/Galeri.svelte';
	import Lokasi from '../organisms/Lokasi.svelte';
	import Footer from '../organisms/Footer.svelte';
</script>

<div class="relative">
	<Header />
	<main class="container px-8 mx-auto mt-24 md:px-0 lg:px-32">
		<Hero />
		<TentangKami />
		<VisiMisi />
		<Galeri />
		<Lokasi />
	</main>
	<Footer />
</div>
