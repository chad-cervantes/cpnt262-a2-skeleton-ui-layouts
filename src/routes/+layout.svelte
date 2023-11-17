<script>
	import '../app.postcss';
	import { AppShell, AppBar, Avatar, LightSwitch } from '@skeletonlabs/skeleton';
	import Custom from '../lib/components/Custom.svelte';
	// import Header from '../lib/components/Header.svelte';
	// import Footer from '../lib/components/Footer.svelte';
	// import PageFooter from '../lib/components/PageFooter.svelte';
</script>

<!-- App Shell -->
<AppShell>
<svelte:fragment slot="header">
	<!-- App Bar -->
	<AppBar gridColumns="grid-cols-1">
	<div class="lg:flex justify-between gap-4 p-4">
		<div>
			<span class="lg:flex items-center">
					<Avatar src="https://images.unsplash.com/photo-1617296538902-887900d9b592?ixid=M3w0Njc5ODF8MHwxfGFsbHx8fHx8fHx8fDE2ODc5NzExMDB8&ixlib=rb-4.0.3&w=128&h=128&auto=format&fit=crop" width="w-10" height="h-10" rounded="rounded-full" />
				<div>
					<span class="text-xl p-1 block">Website Title</span>
				</div> 
			</span>
		</div>
			<nav>
			<ul class="lg:flex flex-end list-none gap-3">
				<li>  
					<a class="btn btn-sm bg-gradient-to-br variant-gradient-primary-secondary border-token" href="/Home">
						Home
					</a>
				</li>
				<li>  
					<a class="btn btn-sm btn-sm bg-gradient-to-br variant-gradient-primary-secondary border-token" href="/Blog">
						Blog
					</a>
				</li>
				<li>  
					<a class="btn btn-sm btn-sm bg-gradient-to-br variant-gradient-primary-secondary border-token" href="/About">
						About
					</a>
				</li>
				<li>
					<a class="btn btn-sm btn-sm bg-gradient-to-br variant-gradient-primary-secondary border-token" href="/History">
						History
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
<Custom />
<svelte:fragment slot="pageFooter">
    <div class="lg:flex justify-center p-4">
      <nav>
        <ul class="flex justify-center list-none gap-4">
          <li>  
            <a
              class="btn btn-sm variant-ghost-surface border-token"
              href="/Home"
            >
              Home
            </a>
          </li>
          <li>  
            <a
              class="btn btn-sm variant-ghost-surface border-token"
              href="/Blog"
            >
              Blog
            </a>
          </li>
          <li>  
            <a
              class="btn btn-sm variant-ghost-surface border-token"
              href="/About"
            >
              About
            </a>
          </li>
         
          <li>
            <a
              class="btn btn-sm variant-ghost-surface border-token"
              href="/History"
            >
              History
            </a>
          </li>
        </ul>
      </nav>  
    </div>      
           

  </svelte:fragment>
	<svelte:fragment slot="footer">
	<div class="lg:flex justify-center text-center p-4">
		&copy; 2023 Chad Cervantes
	</div>
</svelte:fragment>

</AppShell>

<!-- <Header /> -->
<!-- <slot /> -->
<!-- <PageFooter /> -->
<!-- <Footer /> -->
