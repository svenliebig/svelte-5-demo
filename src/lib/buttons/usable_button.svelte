<script lang="ts">
	export let className = "";
</script>

<label
	class={`group select-none flex has-[:checked]:opacity-50 bg-gradient-to-r shadow-lg rounded-sm size-8 items-center justify-center hover:cursor-pointer hover:shadow transition-all ease-out ${className}`}
>
	<input type="checkbox" hidden class="peer" />
	<slot />
</label>
