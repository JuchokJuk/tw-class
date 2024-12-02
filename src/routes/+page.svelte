<script lang="ts">
  let condition = $state(false);
</script>

<button
  class="text-[red]"
  class:bg-[blue]={condition}
  onclick={() => {
    condition = !condition;
  }}
>
  Welcome to SvelteKit
</button>
