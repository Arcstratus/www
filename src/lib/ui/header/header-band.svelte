<script lang="ts">
	import { goto } from '$app/navigation';
	import type { HTMLAttributes } from 'svelte/elements';
	import Logo from '../logo.svelte';

	interface HeaderBandProps extends HTMLAttributes<HTMLDivElement> {
		title: string;
	}

	const { title }: HeaderBandProps = $props();

	const goHome = () => goto('/');
</script>

<button onclick={goHome}>
	<div class="middle flex">
		<Logo />
		<h1 class="scale-75 capitalize">{title}</h1>
	</div>
</button>
