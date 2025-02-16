<script module lang="ts">
  import type { HTMLAttributes } from "svelte/elements";

  interface LinkProps extends HTMLAttributes<HTMLLinkElement> {
    label: string;
    to: string;
  }
</script>

<script>
  import { cn } from "$lib/utils";

  const { label, to }: LinkProps = $props();
</script>

<a href={to} class="relative group bg-black">
  <span class={cn("capitalize", "text-[#9ca3af] group-hover:text-white")}>
    {label}
  </span>
  <span
    class={cn(
      "absolute -bottom-1 inset-x-0 h-0.5 bg-white",
      "transition-[width] duration-300 ease-in-out",
      "w-0 group-hover:w-full",
    )}
  ></span>
</a>
