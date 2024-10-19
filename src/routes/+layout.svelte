<script lang="ts">
	import PageHeader from '$lib/components/pageheader.svelte';
</script>

<PageHeader title="Home" />

<div class="is-flex-grow-1 hero">
	<slot />
</div>

<style lang="scss" scoped>
	.hero {
		background: {
			image: url('/img/ironbridge.jpg');
			position: center center;
			size: cover;
		}
	}
</style>
