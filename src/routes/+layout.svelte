<script lang="ts">
	import { asset, resolve } from '$app/paths'

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={asset('/favicon.jpeg')} />
</svelte:head>

<nav>
	<h1>Copycat</h1>
	<ul>
		<li><a href={resolve('/')}>Home</a></li>
		<li><a href={resolve('/about-me')}>About me</a></li>
		<li><a href={resolve('/portfolio')}>Portfolio</a></li>
		<li><a href={resolve('/contact')}>Contact</a></li>
	</ul>
</nav>

{@render children?.()}
