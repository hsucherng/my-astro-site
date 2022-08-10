<script>
  let name = 'world';
  let count = 0;

  function incrementCount() {
    count += 1;
  }
</script>

<h1>Hello {name}!</h1>

<button on:click={incrementCount}>Clicked {count} times</button>

<style>
  h1 { font-size: 1em; }
</style>
