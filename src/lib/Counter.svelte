<script>
  let count = 1000
  const increment = () => {
    count += 1000000
  }
</script>

<button on:click={increment}>
  Count is {count}
</button>
