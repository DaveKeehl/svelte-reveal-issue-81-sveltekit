<script>
	import { reveal } from 'svelte-reveal';
	
	export let revealConfig = {};
</script>

<div use:reveal={ revealConfig }></div>

<style>
	div {
		width: 100%;
		height: 1px;
		background: rgba(0 0 0 / 0.1);
		margin: 2rem 0;
	}
</style>