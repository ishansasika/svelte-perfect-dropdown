<script>

export let options = [];

</script>

<main>
    <select name="svelte-perfect-select" id="svelte-perfect-select">
        {#each options as option}
            <option value={option.id}>{option.value}</option>
        {/each}
    </select>
  </main>