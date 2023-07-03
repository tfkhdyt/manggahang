<script>
	import clsx from 'clsx';
	import { match } from 'ts-pattern';

	export let roundedPosition;
	export let aspectRatio;
</script>

<div
	class={clsx(
		'absolute top-0 left-0 z-50 w-full bg-gradient-to-r from-orange-800 to-purple-800 rounded opacity-25 transition group-hover:opacity-0  ',
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
