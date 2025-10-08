<script lang="ts">
	import '@fontsource-variable/roboto'
	import '../app.css'

	let { children } = $props()
</script>

<svelte:head>
	<title>CubexsOne</title>
</svelte:head>

<main>
	{@render children?.()}
</main>
