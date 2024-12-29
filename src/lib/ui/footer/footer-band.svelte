<script lang="ts">
	import type { HTMLAttributes } from 'svelte/elements';

	interface FooterBandProps extends HTMLAttributes<HTMLDivElement> {
		title: string;
	}

	const { title }: FooterBandProps = $props();
</script>

<div class="middle flex gap-2">
	<h3 class="capitalize">{title}</h3>
</div>
