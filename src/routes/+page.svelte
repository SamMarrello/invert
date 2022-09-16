<script lang="ts">

    let ctr = 0;
    function add() {
        ctr = ctr + 1;
    }
</script>

<nav></nav>
<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<button on:click={add}>{ctr}</button>
