<script>
  import { AppShell } from '@skeletonlabs/skeleton';
</script>

<AppShell>
	<svelte:fragment slot="header">
		<div class="text-center text-5xl p-4">
			Day of The Dead
		</div>
	</svelte:fragment>
	<!-- (sidebarLeft) -->
	<!-- (sidebarRight) -->
	<!-- Router Slot -->
	<slot />
</AppShell>

