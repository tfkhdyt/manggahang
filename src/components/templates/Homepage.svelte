<script>
	import VisiMisi from '../organisms/VisiMisi.svelte';
	import Lokasi from '../organisms/Lokasi.svelte';
	import Footer from '../organisms/Footer.svelte';
	import Galeri from '../organisms/Galeri.svelte';
	import Hero from '../organisms/Hero.svelte';
	import Header from '../organisms/Header.svelte';
	import TentangKami from '../organisms/TentangKami.svelte';
</script>

<Header />
<main class="container mx-auto lg:px-32">
	<Hero />
	<TentangKami />
	<VisiMisi />
	<Galeri />
	<Lokasi />
</main>
<Footer />
