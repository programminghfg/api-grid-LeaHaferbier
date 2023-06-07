<script>
	export let data;
	let id = data.id;

	let movie = data;
</script>

<a href="/">zurück zur Filmübersicht</a>

<h1>{movie.title}</h1>
<p>{movie.release_date}</p>

<style>
	a {
		color: red;
	}
</style>
