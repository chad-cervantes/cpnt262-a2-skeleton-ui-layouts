<script>
    import { AppShell, AppBar, LightSwitch } from '@skeletonlabs/skeleton';

</script>

<!-- App Shell -->
<AppShell>
  <svelte:fragment slot="header">
    <!-- App Bar -->
    <AppBar gridColumns="grid-cols-1">
       
      
      <!-- <svelte:fragment slot="trail"> -->
				
<div class="lg:flex justify-between gap-4">
	
  			<strong class="text-xl uppercase">
          <a href="/Home">
            Website Title
          </a>
        </strong>
				<nav>
		<ul class="lg:flex list-none gap-4">
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
     
      <li><a
          class="btn btn-sm variant-ghost-surface"
          href="/Contact"
        >
          Contact
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
 
  <svelte:fragment slot="footer">&copy; Chad Cervantes</svelte:fragment>
 
</AppShell>