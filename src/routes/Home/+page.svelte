<script>
  import { AppShell } from '@skeletonlabs/skeleton';
</script>

<AppShell>
	<svelte:fragment slot="header">
		<div class="text-center text-5xl p-4">
			Day of The Dead
		</div>
	</svelte:fragment>
	<div class="m-auto p-4 flex align-center">
		<img src="/images/day-of-the-dead-wikipedia.jpg" alt=""/>
	</div>
	<!-- (sidebarLeft) -->
	<!-- (sidebarRight) -->
	<!-- Router Slot -->
	<slot />
</AppShell>

