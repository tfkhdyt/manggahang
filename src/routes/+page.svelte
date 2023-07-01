<script>
	import '@unocss/reset/tailwind.css';
	import 'virtual:uno.css';
	import '../app.css';

	import Header from '../components/Header.svelte';
	import Hero from '../components/Hero.svelte';
</script>

<svelte:head>
	<title>Manggahang</title>
</svelte:head>

<main class="container mx-auto lg:px-32">
	<Header />
	<Hero />
</main>
