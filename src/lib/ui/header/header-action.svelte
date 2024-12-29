<script lang="ts">
	import { onMount } from 'svelte';
	import { IconUser, IconSun } from '@tabler/icons-svelte';
	import Button from '$lib/components/button/button.svelte';

	let inputElement: HTMLInputElement;

	const handleKeydown = (event: KeyboardEvent) => {
		if (event.ctrlKey && event.key.toLowerCase() == 'k') {
			event.preventDefault();
			inputElement.focus();
		}
	};

	onMount(() => {
		document.addEventListener('keydown', handleKeydown);

		return () => {
			document.removeEventListener('keydown', handleKeydown);
		};
	});
</script>

<div class="middle hidden gap-4 md:flex">
	<Button onclick={() => console.log('lang')}>
		<p>English</p>
	</Button>
	<Button onclick={() => console.log('login')}>
		<IconUser />
	</Button>
	<Button onclick={() => console.log('toggle theme')}>
		<IconSun />
	</Button>
</div>
