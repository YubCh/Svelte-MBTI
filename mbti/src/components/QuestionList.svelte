



<script>
  import QuestionItem from "./QuestionItem.svelte";
  export let questions = []
</script>


{#each questions as q (q.id)}
  <QuestionItem item={q}/>
{/each}