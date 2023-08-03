<script>
    
</script>

<div class="app">
	<main>
		<slot />
	</main>
</div>

<style>
    .app {
        display: flex;
        flex-direction: column;
        height: 100%;
    }

    main {
        flex-grow: 1;
    }
</style>