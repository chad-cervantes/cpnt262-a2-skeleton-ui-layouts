<script>
  import { AppShell } from "@skeletonlabs/skeleton";
</script>

<slot />

<AppShell>
  <svelte:fragment slot="footer">&copy; Chad Cervantes</svelte:fragment>
</AppShell>
