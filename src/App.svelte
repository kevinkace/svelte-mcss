<script>
	import css from './main.css';

	console.log(typeof css); // object
	console.log(css); // {header: "mca712d7b4_header"}
	console.log(css["header"]); // mca712d7b4_header
	console.log(css.header); // css.header
</script>

<main>
	<h1 class={css.header}>class={'{css.header}'} - {css.header}</h1>
	<h1 class={css["header"]}>class={'{css["header"]}'} - {css["header"]}</h1>

	<p>both should have class "mXXX_header" and be green</p>
</main>

<style>
</style>