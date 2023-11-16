<script>
  import { AppShell } from '@skeletonlabs/skeleton';
</script>


<AppShell>
	<svelte:fragment slot="header">
    <div class="text-5xl text-center p-4">
      Blog
    </div>
  </svelte:fragment>
	<svelte:fragment slot="sidebarLeft">
    <div class="p-4">
     <ul class="p-4">
      <li>Costumes</li>
      <li>Decorations</li>
      <li>Themes</li>
      <li>Colors</li>
     </ul>
    </div>
 </svelte:fragment>
	<svelte:fragment slot="sidebarRight">Sidebar Right</svelte:fragment>
	<svelte:fragment slot="pageHeader">
    <div class="text-2xl text-center p-4">
      November Posts
    </div>
  </svelte:fragment>
	<!-- Router Slot -->
	<slot />
	<!-- ---- / ---- -->
	<!-- <svelte:fragment slot="pageFooter">Page Footer</svelte:fragment>
	<svelte:fragment slot="footer">Footer</svelte:fragment> -->
</AppShell>