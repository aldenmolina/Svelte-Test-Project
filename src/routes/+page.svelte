<script>
    let count = 0;

    function handleIncrement() {
        count += 1;
    }
</script>

<h1>Number: {count}</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<button on:click={handleIncrement}>Increment</button>