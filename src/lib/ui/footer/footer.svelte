<script lang="ts">
	import FooterBand from './footer-band.svelte';
	import FooterCopyright from './footer-copyright.svelte';
</script>

<footer class="border-t bg-background/80 p-4">
	<div class="between container mx-auto flex flex-wrap gap-4">
		<FooterBand title="Arcstratus" />
		<FooterCopyright />
	</div>
</footer>
