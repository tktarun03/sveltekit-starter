<script>
    let count = 0;
</script>

<main>
    <h1>Welcome to SvelteKit!</h1>
    <p>Counter: {count}</p>
    <button on:click={() => count++}>Increment</button>
</main>

<style>
    main {
        text-align: center;
        padding: 1rem;
    }
</style>