<script>
	import GetNotified from '@/components/GetNotified.svelte';
</script>

<svelte:head>
	<title>Chochbuech</title>
	<meta
		name="description"
		content="Chochbuech ist eine Schweizer Rezepte-Plattform. Entdecke neue Rezepte, teile deine eigenen Kreationen und lasse dich von der Community inspirieren."
	/>
</svelte:head>

<div class="home wrap">
	<div class="inner">
		<h1>
			Hier entsteht <i>Chochbuech</i>
		</h1>
		<p>
			Bald kannst du neue Rezepte entdecken und deine eigenen Rezepte
			teilen.
			<br />
			Melde dich an, um benachrichtigt zu werden, sobald es losgeht.
		</p>

		<GetNotified />
	</div>
</div>

<style lang="scss">
	.home {
		display: flex;
		height: 100%;
		justify-content: center;
		align-items: center;
	}

	.inner {
		text-align: center;
	}

	h1 {
		font-family: var(--font-secondary);
		font-weight: 200;
		line-height: 1.25;
		font-size: 3rem;
		margin-bottom: 1rem;
	}

	p {
		margin-bottom: 2rem;
		/* font-size: 1.25rem;
		max-width: 30rem; */
	}
</style>
