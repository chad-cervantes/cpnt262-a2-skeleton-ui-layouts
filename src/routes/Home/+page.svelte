<script>
		import { AppShell } from '@skeletonlabs/skeleton';
</script>

<AppShell>
	<svelte:fragment slot="header">
		<div class="text-center text-5xl p-4 bg-primary-400 text-secondary-900">
			Day of The Dead
		</div>
	</svelte:fragment>
	<div class="m-auto p-4 w-full lg:flex justify-center items-center">
		<img src="/images/day-of-the-dead-wikipedia.jpg" alt="day of the dead drawing"/>
	</div>
	<!-- (sidebarLeft) -->
	<!-- (sidebarRight) -->
	<!-- Router Slot -->
	<slot />
</AppShell>