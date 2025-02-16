<script>
  import Logo from "$lib/logo.svelte";
  import { cn } from "$lib/utils.js";
</script>

<header
  class={cn(
    "sticky top-0 z-1000 h-16 p-8 flex middle gap-8",
    "w-full xl:max-w-7xl mx-auto", // container
  )}
>
  <Logo />

  <nav class="hidden lg:block">
    <ul class="flex center middle gap-4">
      <li>Product</li>
      <li>API</li>
      <li>Blog</li>
      <li>About</li>
    </ul>
  </nav>

  <nav class="block lg:hidden ml-auto">
    <button class="active:scale-90">menu</button>

    <ul class="flex-col top gap-4 hidden">
      <li>Product</li>
      <li>API</li>
      <li>Blog</li>
      <li>About</li>
    </ul>
  </nav>
</header>
