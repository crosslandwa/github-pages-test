<script lang="ts">
	import favicon from '$lib/assets/favicon.jpeg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<nav>
	<h1>Copycat</h1>
	<ul>
		<li><a href="/">Home</a></li>
		<li><a href="/about-me">About me</a></li>
		<li><a href="/portfolio">Portfolio</a></li>
		<li><a href="/contact">Contact</a></li>
	</ul>
</nav>

{@render children?.()}
