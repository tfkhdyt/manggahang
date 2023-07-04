<script>
	import NormalItem from '../../atoms/lists/NormalItem.svelte';
	import BoldText from '../../atoms/typography/BoldText.svelte';
	import Subtitle from '../../atoms/typography/Subtitle.svelte';
	import GradientImage from '../GradientImage.svelte';
</script>

<div class="flex flex-col gap-6 md:flex-row md:gap-12">
	<div class="space-y-4 md:w-1/2">
		<div>
			<BoldText>Visi</BoldText>
			<Subtitle>Sebagai pusat pengembangan jasa yang utama di Kabupaten Bandung.</Subtitle>
		</div>
		<BoldText>Misi</BoldText>
		<Subtitle>
			<ul class="ml-6 space-y-2 list-disc list-outside">
				<NormalItem>
					Meningkatkan penyelenggaraan pemerintah dan pelayanan prima yang profesional.
				</NormalItem>
				<NormalItem>
					Membangun kehidupan sosial yang harmonis dengan ditunjang partisipasi Masyarakat yang
					Terus Meningkat.
				</NormalItem>
				<NormalItem>
					Meningkatkan penataan lingkungan kecamatan, terutama lingkungan pemukiman yang
					berkelanjutan.
				</NormalItem>
			</ul>
		</Subtitle>
	</div>
	<div class="md:w-1/2">
		<GradientImage
			src="/img/pemandangan.jpg"
			alt="Pemandangan dari atas"
			roundedPosition="br"
			className="aspect-[4/3] md:aspect-[5/6] lg:aspect-[4/3]"
		/>
	</div>
</div>
