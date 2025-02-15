<script>
  import { i18n } from "$lib/i18n";
  import { ParaglideJS } from "@inlang/paraglide-sveltekit";
  import "../app.css";
  let { children } = $props();
</script>

<svelte:head>
  <title>Arcstratus</title>
</svelte:head>

<ParaglideJS {i18n}>
  {@render children()}
</ParaglideJS>
