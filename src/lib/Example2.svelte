<script>
	import { reveal } from 'svelte-reveal';
	import Label from './Label.svelte'
</script>

<div class="docs" use:reveal={{ delay: 2500 }}>
	<Label>Example 2</Label>
	<p>With svelte-reveal you can create custom transitions that get triggered when the element becomes visible.</p>
	<p>You can get some really nice effects by playing with the many <a href="https://github.com/DaveKeehl/svelte-reveal/blob/main/src/internal/config.ts#L6-L37">options</a> this library offers.</p>
	<p>In particular, elements can use the following transitions:</p>
	<ul>
		<li><p use:reveal={{ transition: "fly", delay: 3000 }}>Fly</p></li>
		<li><p use:reveal={{ transition: "slide", delay: 3500 }}>Slide</p></li>
		<li><p use:reveal={{ transition: "fade", delay: 4000 }}>Fade</p></li>
		<li><p use:reveal={{ transition: "blur", delay: 4500 }}>Blur</p></li>
		<li><p use:reveal={{ transition: "scale", delay: 5000 }}>Scale</p></li>
		<li><p use:reveal={{ transition: "spin", delay: 5500 }}>Spin</p></li>
	</ul>	
</div>

<style>	
	li p {
		line-height: 0;
	}
	
	a {
		text-decoration: underline;
	}
	
	.docs {
		display: block;
		padding-bottom: 1rem;
	}
</style>