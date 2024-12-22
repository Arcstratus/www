<script lang="ts">
	import { i18n } from '$lib/i18n';
	import { ParaglideJS } from '@inlang/paraglide-sveltekit';
	import '../app.css';
	let { children } = $props();
</script>

<ParaglideJS {i18n}>
	<div class="gird h-screen grid-rows-[auto_1fr_auto]">
		<header class="sticky top-0 z-10 px-8 py-4 backdrop-blur-sm">
			<div class="between middle mx-auto flex w-full gap-4"></div>
		</header>

		<main class="space-y-4 p-4">
			{@render children()}
		</main>

		<footer class="px-8 py-4">
			<div class="middle between mx-auto flex w-full gap-4"></div>
		</footer>
	</div>
</ParaglideJS>
