<script>
	import Goal from "./Goal.Svelte.svelte"
					
  let goal;
</script>

<input type="text" bind:value={goal} />
<Goal goal={goal} />
