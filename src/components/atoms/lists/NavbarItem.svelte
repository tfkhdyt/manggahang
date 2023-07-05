<script>
	export let onClick;
</script>

<button on:click={onClick} class="text-left">
	<slot />
</button>
