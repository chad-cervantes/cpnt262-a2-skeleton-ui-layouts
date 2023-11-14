<script>
  import Footer from "../../lib/components/Footer.svelte";
  import Header from "../../lib/components/Header.svelte";
  import { AppShell } from '@skeletonlabs/skeleton';
</script>

<Header />


<AppShell>
	<svelte:fragment slot="header">Home</svelte:fragment>
	<!-- (sidebarLeft) -->
	<!-- (sidebarRight) -->
	<!-- Router Slot -->
	<slot />
</AppShell>

<Footer />