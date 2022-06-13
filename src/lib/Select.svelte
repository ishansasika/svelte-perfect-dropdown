<script>

export let options = [];
export let selectSize = "";
</script>

<main>
    <select class={selectSize} name="svelte-perfect-select" id="svelte-perfect-select">
        {#each options as option}
            <option value={option.id}>{option.value}</option>
        {/each}
    </select>
</main>

<style>
    .smaller{
        font-size: 10px;
    }
    .small{
        font-size: 12px;
    }
    .medium{
        font-size: 15px;
    }
    .large{
        font-size: 18px;
    }
    .larger{
        font-size: 20px;
    }
</style>