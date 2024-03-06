<script lang="ts">
  let count = 0;

  function handleClick() {
    count += 1;
  }
  const value = import.meta.env.VITE_LOCAL_VARIABLE_TEST2
</script>

<h3>From UI 2</h3>
<button on:click={handleClick}>
  clicks: {count}
</button>
<p>value from ui2 : {value}</p>
