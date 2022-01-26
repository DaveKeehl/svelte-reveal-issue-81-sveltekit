<script>
	import { setDefaultOptions } from 'svelte-reveal'
	
	import Example1 from './Example1.svelte'
	import Example2 from './Example2.svelte'
	import Example3 from './Example3.svelte'
	import Divider from './Divider.svelte'
	
	setDefaultOptions({
		easing: 'easeOutCubic',
		duration: 500
	})
</script>

<Example1 />
<Divider revealConfig={{ delay: 1860 }} />
<Example2 />
<Divider />
<Example3 />