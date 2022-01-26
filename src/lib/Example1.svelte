<script>
	import { reveal } from 'svelte-reveal';
	import Label from './Label.svelte'
</script>

<Label>Example 1</Label>
<h1 use:reveal={{ delay: 50 }}>Welcome to this demo!</h1>
<h2 use:reveal={{ delay: 100 }}>After you read this.</h2>
<div class="box">
	<h3 use:reveal={{ delay: 600}}>You'll read this</h3>
	<h3 use:reveal={{ delay: 1200}}>... and then this.</h3>
</div>
<p use:reveal={{ delay: 1800 }}>Pretty cool, huh? 😎</p>

<style>
	p {
		line-height: 1.75rem
	}
	
	h1 {
		display: block;
		font-size: 4rem;
		margin: 1.5rem 0;
	}
	
	h2 {
		font-size: 2.5rem;
		margin-bottom: 0;
	}
	
	h3 {
		font-size: 2rem;
		margin-bottom: 0;
	}
	
	.box {
		display: flex;
		gap: 1rem;
		margin-bottom: 2rem;
	}
</style>