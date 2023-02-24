<script>

	import QuestionList from "./components/QuestionList.svelte";
	let questions = [{
		id: '1'},
		{id: '2'},
		{id: '3'}];
</script>

<main>
<QuestionList questions = {questions}/>
	


</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>