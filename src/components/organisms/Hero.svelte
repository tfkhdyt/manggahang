<script>
	import GradientImage from '../molecules/GradientImage.svelte';
	import Introduction from '../molecules/Introduction.svelte';
	import Stat from '../molecules/Stat.svelte';
</script>

<section class="flex flex-col gap-12 items-end pt-6 pb-16 md:flex-row md:gap-0">
	<div class="space-y-6 md:space-y-10 md:w-1/2">
		<Introduction />
		<div class="flex pt-6 space-x-6 md:space-x-8 lg:pt-12">
			<Stat title="Total penduduk" value="±38 rb" />
			<Stat title="Suhu Rata-rata" value="27 °C" />
		</div>
	</div>
	<div class="space-y-4 md:pl-8 md:w-1/2">
		<div class="ml-auto md:w-11/12 lg:w-5/6">
			<GradientImage
				src="/img/gunung-geulis.jpg"
				alt="Gunung geulis"
				roundedPosition="t"
				className="aspect-[3/1]"
			/>
		</div>
		<div class="ml-auto md:w-11/12 lg:w-5/6">
			<GradientImage src="/img/lapang-carik.jpg" alt="Lapangan Carik" className="aspect-[2.5/1]" />
		</div>
		<div class="ml-auto md:w-11/12 lg:w-5/6">
			<GradientImage
				src="/img/kantor-kelurahan.jpg"
				alt="Kantor kelurahan"
				roundedPosition="b"
				className="aspect-[4/3]"
			/>
		</div>
	</div>
</section>
