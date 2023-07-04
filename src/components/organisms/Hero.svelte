<script>
	import GradientImage from '../molecules/GradientImage.svelte';
	import Introduction from '../molecules/Introduction.svelte';
	import Stat from '../molecules/Stat.svelte';
</script>

<section class="flex items-end pt-6 pb-16">
	<div class="space-y-10 w-1/2">
		<Introduction />
		<div class="flex pt-12 space-x-8">
			<Stat title="Total penduduk" value="38 rb" />
			<Stat title="Suhu Rata-rata" value="27 °C" />
		</div>
	</div>
	<div class="pl-8 space-y-4 w-1/2">
		<GradientImage
			src="/img/gunung-geulis.jpg"
			alt="Gunung geulis"
			roundedPosition="t"
			className="aspect-[3/1]"
		/>
		<GradientImage src="/img/lapang-carik.jpg" alt="Lapangan Carik" className="aspect-[2.5/1]" />
		<GradientImage
			src="/img/kantor-kelurahan.jpg"
			alt="Kantor kelurahan"
			roundedPosition="b"
			className="aspect-[4/3]"
		/>
	</div>
</section>
