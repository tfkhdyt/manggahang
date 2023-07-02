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

	import Header from '../components/Header.svelte';
	import Hero from '../components/Hero.svelte';
	import TentangKami from '../components/TentangKami.svelte';
</script>

<svelte:head>
	<title>Manggahang</title>
</svelte:head>

<main class="container mx-auto lg:px-32">
	<Header />
	<Hero />
	<TentangKami />
</main>
