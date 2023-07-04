<script>
	import NormalItem from '../../atoms/lists/NormalItem.svelte';
	import BoldText from '../../atoms/typography/BoldText.svelte';
	import Subtitle from '../../atoms/typography/Subtitle.svelte';
	import GradientImage from '../GradientImage.svelte';
</script>

<div class="space-y-8 w-1/2">
	<GradientImage
		src="/img/manggahang-1.jpg"
		alt="SDN Manggahang 1"
		roundedPosition="tl"
		className="aspect-[2/1]"
	/>
	<div class="space-y-4">
		<div>
			<BoldText>Visi</BoldText>
			<Subtitle>Sebagai pusat pengembangan jasa yang utama di Kabupaten Bandung.</Subtitle>
		</div>
		<BoldText>Misi</BoldText>
		<Subtitle>
			<ul class="ml-6 space-y-2 list-disc list-outside">
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
</div>
