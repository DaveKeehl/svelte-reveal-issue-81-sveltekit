<script>
	import { reveal } from 'svelte-reveal'
	
	export let revealConfig = null
</script>

<p use:reveal={ revealConfig }><slot/></p>

<style>
	p {
		display: flex;
		background: violet;
		color: white;
		font-weight: bold;
		margin-bottom: 0;
		width: fit-content;
		padding: 0.25rem 0.5rem;
	}
</style>