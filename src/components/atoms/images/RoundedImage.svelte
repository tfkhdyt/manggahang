<script>
	import clsx from 'clsx';
	import { match } from 'ts-pattern';

	export let roundedPosition;
	export let src;
	export let alt;
	export let className = '';
</script>

<img
	{src}
	{alt}
	class={clsx(
		'object-cover object-center mx-auto w-full rounded transition  grayscale group-hover:grayscale-0',
		match(roundedPosition)
			.with('t', () => 'rounded-t-[2rem] md:rounded-t-[4rem]')
			.with('l', () => 'rounded-l-[2rem] md:rounded-l-[4rem]')
			.with('r', () => 'rounded-r-[2rem] md:rounded-r-[4rem]')
			.with('b', () => 'rounded-b-[2rem] md:rounded-b-[4rem]')
			.with('tl', () => 'rounded-tl-[2rem] rounded-tl-[4rem]')
			.with('tr', () => 'rounded-tr-[2rem] rounded-tr-[4rem]')
			.with('bl', () => 'rounded-bl-[2rem] rounded-bl-[4rem]')
			.with('br', () => 'rounded-br-[2rem] rounded-br-[4rem]')
			.with('none', () => '')
			.exhaustive(),
		className
	)}
/>
