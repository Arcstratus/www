<script>
  import { cn } from "$lib/utils.js";
  import Logo from "$lib/logo.svelte";
  import Link from "$lib/component/link.svelte";
</script>

<header
  class={cn("sticky top-0 z-1000 h-16 p-8 flex middle gap-8", "container")}
>
  <Logo />

  <nav class="hidden lg:block">
    <ul class="flex center middle gap-4 text-lg">
      <li>
        <Link to="/product" label="product" />
      </li>
      <li>
        <Link to="/api" label="label" />
      </li>
      <li>
        <Link to="/blog" label="blog" />
      </li>
      <li>
        <Link to="/about" label="about" />
      </li>
    </ul>
  </nav>

  <nav class="block lg:hidden ml-auto">
    <button class="active:scale-90">menu</button>

    <ul class="flex-col top gap-4 hidden">
      <li>
        <Link to="/product" label="product" />
      </li>
      <li>
        <Link to="/api" label="label" />
      </li>
      <li>
        <Link to="/blog" label="blog" />
      </li>
      <li>
        <Link to="/about" label="about" />
      </li>
    </ul>
  </nav>
</header>
