<script>
  import Footer from "../../lib/components/Footer.svelte";
  import Header from "../../lib/components/Header.svelte";
  import { AppShell } from '@skeletonlabs/skeleton';
</script>

<Header />


<AppShell>
	<svelte:fragment slot="header">Header</svelte:fragment>
	<!-- (sidebarLeft) -->
	<!-- (sidebarRight) -->
	<svelte:fragment slot="pageHeader">Page Header</svelte:fragment>
	<!-- Router Slot -->
	<slot />
</AppShell>

<Footer />