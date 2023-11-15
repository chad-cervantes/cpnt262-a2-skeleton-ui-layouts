<script>
  import { AppShell } from "@skeletonlabs/skeleton";
</script>

<AppShell>
	<!-- (header) -->
	<!-- (sidebarLeft) -->
	<!-- (sidebarRight) -->
	<!-- (pageHeader) -->
	<!-- Router Slot -->
	<slot />
	<!-- ---- / ---- -->
	<svelte:fragment slot="pageFooter">
    <div class="lg:flex justify-center p-4">
      <nav>
        <ul class="flex justify-center list-none gap-4">
          <li>  
            <a
              class="btn btn-sm variant-ghost-surface"
              href="/Home"
            >
              Home
            </a>
          </li>
          <li>  
            <a
              class="btn btn-sm variant-ghost-surface"
              href="/About"
            >
              About
            </a>
          </li>
         
          <li>
            <a
              class="btn btn-sm variant-ghost-surface"
              href="/History"
            >
              History
            </a>
          </li>
        </ul>
      </nav>  
    </div>      
           

  </svelte:fragment>
	<!-- (footer) -->
</AppShell>