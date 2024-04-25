<script lang="ts">
	import type { ComponentType } from "svelte";

	export let icon;

	const Icon: ComponentType = icon;
</script>

<div class="relative">
	<Icon className="peer-checked:opacity-0 absolute blur-sm group-hover:blur-0 transition-all ease-out opacity-50" />
	<Icon className="peer-checked:fill-gray-400 transition-all ease-out" />
</div>
