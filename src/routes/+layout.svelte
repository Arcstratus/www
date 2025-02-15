<script>
  import { i18n } from "$lib/i18n";
  import { ParaglideJS } from "@inlang/paraglide-sveltekit";
  import Header from "$lib/ui/header.svelte";
  import Footer from "$lib/ui/footer.svelte";
  import "../app.css";

  let { children } = $props();
</script>

<svelte:head>
  <title>Arcstratus</title>
</svelte:head>

<ParaglideJS {i18n}>
  <Header />
  <main>
    {@render children()}
  </main>
  <Footer />
</ParaglideJS>
