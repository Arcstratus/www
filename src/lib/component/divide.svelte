<script module lang="ts">
  export interface DivideProps {
    label?: string;
  }
</script>

<script lang="ts">
  const { label }: DivideProps = $props();
</script>

<div class="flex center middle my-4 gap-4">
  {#if label}
    <span class="text-2xl">{label}</span>
  {/if}
  <span class="flex-grow h-[1px] bg-foreground"></span>
</div>
