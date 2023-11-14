<script>
    import { AppShell, AppBar, Avatar, LightSwitch } from '@skeletonlabs/skeleton';

</script>

<!-- App Shell -->
<AppShell>
  <svelte:fragment slot="header">
    <!-- App Bar -->
    <AppBar gridColumns="grid-cols-1">
       
      
      <!-- <svelte:fragment slot="trail"> -->
				
<div class="lg:flex justify-between gap-4">
	
  			<div class="p-3">
          <a href="/Home">
            <Avatar src="https://images.unsplash.com/photo-1617296538902-887900d9b592?ixid=M3w0Njc5ODF8MHwxfGFsbHx8fHx8fHx8fDE2ODc5NzExMDB8&ixlib=rb-4.0.3&w=128&h=128&auto=format&fit=crop" width="w-10" height="h-10" rounded="rounded-full" />
          </a>
        </div>
				<nav>
		<ul class="lg:flex list-none gap-4 p-4">
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
       
      <li>
        <a
          class="btn btn-sm variant-ghost-surface"
          href="/Gallery"
        >
          Gallery
        </a>
      </li>
			<LightSwitch class="mt-1"/>
		</ul>
		
  </nav>  
</div>      
       
      <!-- </svelte:fragment> -->
    </AppBar>
  </svelte:fragment>
  <!-- Page Route Content -->

	<slot />
 
 
</AppShell>