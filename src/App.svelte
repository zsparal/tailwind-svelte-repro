<script lang="ts">
  let bold = false;
</script>

<div class="h-screen w-screen flex items-center justify-center">
  <button on:click={() => bold = !bold}>Toggle</button>
  <h1 class:font-medium={bold}>Hello, World</h1>
</div>
