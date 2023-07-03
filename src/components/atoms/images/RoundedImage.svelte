<script>
	import clsx from 'clsx';
	import { match } from 'ts-pattern';

	export let roundedPosition = '';
	export let aspectRatio;
	export let src;
	export let alt;
</script>

<img
	{src}
	{alt}
	class={clsx(
		'object-cover object-center mx-auto w-full rounded transition  grayscale group-hover:grayscale-0',
		match(roundedPosition)
			.with('t', () => 'rounded-t-[4rem]')
			.with('l', () => 'rounded-l-[4rem]')
			.with('r', () => 'rounded-r-[4rem]')
			.with('b', () => 'rounded-b-[4rem]')
			.with('tl', () => 'rounded-tl-[4rem]')
			.with('tr', () => 'rounded-tr-[4rem]')
			.with('bl', () => 'rounded-bl-[4rem]')
			.with('br', () => 'rounded-br-[4rem]')
			.otherwise(() => ''),
		`aspect-[${aspectRatio}]`
	)}
/>
