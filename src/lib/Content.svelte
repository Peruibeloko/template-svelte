<script lang="ts">
  let count: number = 0;
  const increment = () => {
    count += 1;
  };
</script>

<button on:click={increment}>
  count is {count}
</button>

<style scoped>
  button {
  border: none;
  color: var(--foreground);
  background-color: transparent;
  font-family: monospace;
  font-size: 2rem;
  border: 5px solid var(--main);
  padding: 1rem;
  border-radius: 1rem;
  transition-duration: 200ms;
}

button:hover {
  color: var(--background);
  background-color: var(--foreground);
}
</style>