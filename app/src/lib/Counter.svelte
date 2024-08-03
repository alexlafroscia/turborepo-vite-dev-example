<script lang="ts">
  import { add } from "compiled-package";

  let count: number = 0;

  const increment = () => {
    count = add(count, 1);
  };
</script>

<button on:click={increment}>
  count is {count}
</button>
