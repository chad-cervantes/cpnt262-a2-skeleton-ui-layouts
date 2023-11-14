<script>
  import { AppShell } from "@skeletonlabs/skeleton";
</script>


<AppShell>
	<svelte:fragment slot="header">
    <div class="text-center text-5xl p-4">
      About
    </div>
  </svelte:fragment>
	<!-- (sidebarLeft) -->
	<!-- (sidebarRight) -->
	<!-- (pageHeader) -->
	<!-- Router Slot -->
	<slot />
	<!-- ---- / ---- -->
	<!-- (pageFooter) -->
	<!-- (footer) -->
</AppShell>