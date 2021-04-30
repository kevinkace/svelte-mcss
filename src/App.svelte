<script>
	import Comp1 from './comp1/Comp1.svelte';
	import css from './main.css';

	export let name;

	console.log(css);
</script>

<main>
	<h1 class={css.header}>Hello {name}!</h1>

	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>

	<Comp1 />
</main>

<style>
</style>