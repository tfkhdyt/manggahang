<script>
	import Stat from './Stat.svelte';
</script>

<div class="flex items-end py-6">
	<div class="space-y-10 w-1/2">
		<h1 class="max-w-md font-bold md:text-4xl lg:text-6xl lg:leading-snug">
			Selamat Datang di Manggahang!
		</h1>
		<p class="max-w-md text-xl leading-relaxed text-gray-600">
			Manggahang adalah sebuah kelurahan di kecamatan Baleendah, Bandung, Jawa Barat, Indonesia.
		</p>
		<div class="flex pt-12 space-x-8">
			<Stat title="Total penduduk" value="38 rb" />
			<Stat title="Suhu Rata-rata" value="27 °C" />
		</div>
	</div>
	<div class="pl-8 space-y-4 w-1/2">
		<div class="relative ml-auto w-5/6 group">
			<div
				class="absolute top-0 left-0 z-50 w-full bg-gradient-to-r from-red-800 to-purple-800 rounded-b opacity-25 transition group-hover:opacity-0 rounded-t-[3rem] aspect-[3/1]"
			/>
			<img
				src="/img/gunung-geulis.jpg"
				alt="Gunung geulis"
				class="object-cover object-center mx-auto w-full rounded-b transition rounded-t-[3rem] aspect-[3/1] grayscale group-hover:grayscale-0"
			/>
		</div>
		<div class="relative ml-auto w-5/6 group">
			<div
				class="absolute top-0 left-0 z-50 w-full bg-gradient-to-r from-red-800 to-purple-800 rounded opacity-25 transition group-hover:opacity-0 aspect-[2.5/1]"
			/>
			<img
				src="/img/lapang-carik.jpg"
				alt="Gunung geulis"
				class="object-cover object-center mx-auto w-full rounded transition aspect-[2.5/1] grayscale group-hover:grayscale-0"
			/>
		</div>
		<div class="relative ml-auto w-5/6 group">
			<div
				class="absolute top-0 left-0 z-50 w-full bg-gradient-to-r from-red-800 to-purple-800 rounded-t opacity-25 transition group-hover:opacity-0 rounded-b-[3rem] aspect-[4/3]"
			/>
			<img
				src="/img/kantor-kelurahan.jpg"
				alt="Gunung geulis"
				class="object-cover object-center mx-auto w-full rounded-t transition rounded-b-[3rem] aspect-[4/3] grayscale group-hover:grayscale-0"
			/>
		</div>
	</div>
</div>
