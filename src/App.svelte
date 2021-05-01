<script>
	import css from './main.css';

	export let name;

	console.log(typeof css);
	console.log(css);
	console.log(css.header);
	console.log(css["header"]);
</script>

<main>
	<h1 class={css.header}>class={css.header}</h1>
	<h1 class={css["header"]}>class={css["header"]}</h1>
	<p>both should have class "header" and be green</p>
</main>

<style>
</style>