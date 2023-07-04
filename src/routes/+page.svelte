<script>
	import '@unocss/reset/tailwind.css';
	import 'virtual:uno.css';
	import '@fontsource/poppins/100.css';
	import '@fontsource/poppins/200.css';
	import '@fontsource/poppins/300.css';
	import '@fontsource/poppins/400.css';
	import '@fontsource/poppins/500.css';
	import '@fontsource/poppins/600.css';
	import '@fontsource/poppins/700.css';
	import '@fontsource/poppins/800.css';
	import '@fontsource/poppins/900.css';
	import '../app.css';

	import VisiMisi from '../components/organisms/VisiMisi.svelte';
	import Galeri from '../components/Galeri.svelte';
	import Lokasi from '../components/Lokasi.svelte';
	import Footer from '../components/organisms/Footer.svelte';
	import Hero from '../components/organisms/Hero.svelte';
	import Header from '../components/organisms/Header.svelte';
	import TentangKami from '../components/organisms/TentangKami.svelte';
</script>

<svelte:head>
	<title>Manggahang</title>
</svelte:head>

<main class="container mx-auto lg:px-32">
	<Header />
	<Hero />
	<TentangKami />
	<VisiMisi />
	<Galeri />
	<Lokasi />
</main>
<Footer />
