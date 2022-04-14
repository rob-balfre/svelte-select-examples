<script>
  import "svelte-select/tailwind.css";
  import Select from "svelte-select/no-styles/Select.svelte";
  let items = ['One', 'Two', 'Three'];

</script>

<div class="container mx-auto p-3">
  <h1 class="text-3xl font-bold mb-2">
    SvelteKit + tailwind + svelte-select
  </h1>

  <Select {items} />
</div>
