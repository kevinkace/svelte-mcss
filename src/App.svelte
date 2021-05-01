<script>
	import css from './main.css';

	console.log(typeof css); // object
	console.log(css); // {header: "mca712d7b4_header"}
	console.log(css["header"]); // mca712d7b4_header
	console.log(css.header); // css.header
</script>

<main>
	⚠ inner quotes are a lie 👇
	<h1 class={css.header}>class=&lbrace;css.header&rbrace;</h1>
	<h1 class="{css.header}">class="&lbrace;css.header&rbrace;"</h1>
	<h1 class={css["header"]}>class=&lbrace;css["header"]&rbrace;</h1>

	<p>both should have class "mXXX_header" and be green</p>
</main>

<style>
</style>