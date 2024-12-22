<script lang="ts">
	import { i18n } from '$lib/i18n';
	import { Footer, Header } from '$lib/ui';
	import { ParaglideJS } from '@inlang/paraglide-sveltekit';
	import '../app.css';

	let { children } = $props();
</script>

<svelte:head>
	<title>Arcstratus</title>
</svelte:head>

<ParaglideJS {i18n}>
	<div class="gird h-screen grid-rows-[auto_1fr_auto]">
		<Header />

		<main class="space-y-4 p-4">
			{@render children()}
		</main>

		<Footer />
	</div>
</ParaglideJS>
