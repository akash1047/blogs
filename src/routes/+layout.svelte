<main class="flex-1">
	<slot />
</main>

<style>
	:global(html) {
		height: 100%;
	}

	:global(body) {
		height: 100%;
		display: flex;
		flex-direction: column;
	}
</style>
