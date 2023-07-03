<script>
	import Stat from '../Stat/Stat.svelte';
	import Subtitle from '../../atoms/typography/Subtitle.svelte';
	import Title from '../../atoms/typography/Title.svelte';
</script>

<div class="space-y-10 w-1/2">
	<Title>Selamat Datang di Manggahang!</Title>
	<Subtitle>
		Manggahang adalah sebuah kelurahan di kecamatan Baleendah, Bandung, Jawa Barat, Indonesia.
	</Subtitle>
	<div class="flex pt-12 space-x-8">
		<Stat title="Total penduduk" value="38 rb" />
		<Stat title="Suhu Rata-rata" value="27 °C" />
	</div>
</div>
