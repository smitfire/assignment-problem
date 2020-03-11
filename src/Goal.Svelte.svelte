<script>
    export let goal = 'placeholder';

    $: hasExclamationMark = goal.includes("!");
</script>

<style>
  .red {
    color: red;
  }
</style>

<h1 class={hasExclamationMark ? 'red' : 'normal'}>{goal}</h1>
