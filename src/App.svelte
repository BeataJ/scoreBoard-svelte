<script>
  let name = 'Joe Doe';
  let points = 100;
</script>

<style>
  h1 {
    color: #204f6e;
  }
</style>

<div class="container">
  <div class="card">
    <h1>{name}</h1>
    <h3>{points}</h3>
    <button class="btn" on:click={addPoint}>+1</button>
    <button class="btn btn-dark" on:click={removePoint}>-1</button>
  </div>
</div>
