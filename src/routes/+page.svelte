<script>
	import UsableButton from "$lib/buttons/usable_button.svelte";
	import ActionIcon from "$lib/icons/action_icon.svelte";
	import BonusActionIcon from "$lib/icons/bonus_action_icon.svelte";
	import DimmableIcon from "$lib/icons/dimmable_icon.svelte";
	import SpellIcon from "$lib/icons/spell_icon.svelte";
</script>

<div class="p-1">
	<h3>Actions</h3>
	<div class="flex gap-3">
		<UsableButton className="from-sky-400 to-sky-500">
			<DimmableIcon icon={ActionIcon} />
		</UsableButton>
		<UsableButton className="from-indigo-700 to-indigo-900">
			<DimmableIcon icon={BonusActionIcon} />
		</UsableButton>
	</div>
	<h3>Spellslots Level 1</h3>
	<div class="flex gap-3">
		<UsableButton className="from-amber-800 to-amber-900">
			<DimmableIcon icon={SpellIcon} />
		</UsableButton>
		<UsableButton className="from-amber-800 to-amber-900">
			<DimmableIcon icon={SpellIcon} />
		</UsableButton>
	</div>
	<h3>Spellslots Level 2</h3>
	<div class="flex gap-3">
		<UsableButton className="from-amber-800 to-amber-900">
			<DimmableIcon icon={SpellIcon} />
			<DimmableIcon icon={SpellIcon} />
		</UsableButton>
		<UsableButton className="from-amber-800 to-amber-900">
			<DimmableIcon icon={SpellIcon} />
			<DimmableIcon icon={SpellIcon} />
		</UsableButton>
	</div>
	<h3>Spellslots Level 3</h3>
	<div class="flex gap-3">
		<UsableButton className="from-amber-800 to-amber-900 grid grid-cols-2 grid-rows-2">
			<DimmableIcon icon={SpellIcon} />
			<DimmableIcon icon={SpellIcon} />
			<DimmableIcon icon={SpellIcon} />
		</UsableButton>
		<UsableButton className="from-amber-800 to-amber-900 grid grid-cols-2 grid-rows-2">
			<DimmableIcon icon={SpellIcon} />
			<DimmableIcon icon={SpellIcon} />
			<DimmableIcon icon={SpellIcon} />
		</UsableButton>
	</div>
	<h3>Spellslots Level 4</h3>
	<div class="flex gap-3">
		<UsableButton className="from-amber-800 to-amber-900 grid grid-cols-2 grid-rows-2">
			<DimmableIcon icon={SpellIcon} />
			<DimmableIcon icon={SpellIcon} />
			<DimmableIcon icon={SpellIcon} />
			<DimmableIcon icon={SpellIcon} />
		</UsableButton>
		<UsableButton className="from-amber-800 to-amber-900 grid grid-cols-2 grid-rows-2">
			<DimmableIcon icon={SpellIcon} />
			<DimmableIcon icon={SpellIcon} />
			<DimmableIcon icon={SpellIcon} />
			<DimmableIcon icon={SpellIcon} />
		</UsableButton>
	</div>
</div>
