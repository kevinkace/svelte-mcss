<script>
	import css from './comp1.css';

	console.log(css.comp1);
	console.log(typeof css);
	console.log(css);
	console.log(css["comp1"]);
</script>

<dev>
	<p class={css["comp1"]}>Hello comp1!</p>
	<p class={css.comp1}>Hello comp1!</p>
</dev>
