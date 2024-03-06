<script lang="ts">
  let count = 0;

  function handleClick() {
    count += 1;
  }
</script>

<h3>From UI 2</h3>
<button on:click={handleClick}>
  clicks: {count}
</button>
