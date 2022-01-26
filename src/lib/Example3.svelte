<script>
	import { reveal } from 'svelte-reveal';
	import Label from './Label.svelte'
</script>

<div>
	<Label>Example 3</Label>
	<p use:reveal>At this point the content of this demo should be long enough to be out of view when you first load the page. As a result, the Intersection Observer kicks in and adds the transitions only when the elements are in view.</p>
</div>

<style>
	div {
		padding-bottom: 1rem;
	}
</style>
