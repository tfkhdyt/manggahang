<script>
	import { twMerge } from 'tailwind-merge';

	import NavbarItem from '../../atoms/lists/NavbarItem.svelte';

	export let className = '';

	const scrollToSection = (id) => {
		try {
			document.getElementById(id).scrollIntoView({
				behavior: 'smooth'
			});
		} catch (error) {
			if (error instanceof Error) {
				return console.error(error.message);
			}
			return console.error(error);
		}
	};
</script>

<div class={twMerge('md:space-x-6 lg:space-x-12', className)}>
	<NavbarItem onClick={() => scrollToSection('home')}>Home</NavbarItem>
	<NavbarItem onClick={() => scrollToSection('tentang-kami')}>Tentang Kami</NavbarItem>
	<NavbarItem onClick={() => scrollToSection('visi-misi')}>Visi Misi</NavbarItem>
	<NavbarItem onClick={() => scrollToSection('galeri')}>Galeri</NavbarItem>
	<NavbarItem onClick={() => scrollToSection('lokasi')}>Lokasi</NavbarItem>
</div>
