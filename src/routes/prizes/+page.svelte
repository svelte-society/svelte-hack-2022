<script>
	import BlobA from '$lib/graphics/BlobA.svelte';
	import { Prizes } from '$lib/components';
</script>

<section>
	<div class="br-sm" />

	<h1>Prizes</h1>

	<div class="br-md" />

	<Prizes />

	<div class="blob-a">
		<BlobA />
	</div>

	<div class="br-lg" />
</section>

<style>
	h1 {
		font-size: var(--font-xxl);
		text-align: center;
	}

	.blob-a {
		position: absolute;
		bottom: -30%;
		left: 0;
		z-index: -1;
	}

	section {
		position: relative;
		display: flex;
		flex-direction: column;
		flex-grow: 1;

		margin: 0 auto;
		min-width: 100vw;
		padding-bottom: 5rem;

		overflow: hidden;
	}
</style>
