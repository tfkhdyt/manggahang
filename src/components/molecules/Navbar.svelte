<script>
	import { twMerge } from 'tailwind-merge';
	import NavbarItem from '../atoms/lists/NavbarItem.svelte';

	export let className = '';
</script>

<div class={twMerge('md:space-x-6 lg:space-x-12', className)}>
	<NavbarItem href="#home">Home</NavbarItem>
	<NavbarItem href="#tentang-kami">Tentang Kami</NavbarItem>
	<NavbarItem href="#visi-misi">Visi Misi</NavbarItem>
	<NavbarItem href="#galeri">Galeri</NavbarItem>
	<NavbarItem href="#lokasi">Lokasi</NavbarItem>
</div>
