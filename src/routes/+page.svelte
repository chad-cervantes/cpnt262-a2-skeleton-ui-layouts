<!-- YOU CAN DELETE EVERYTHING IN THIS PAGE -->

<script>  
	import { AppShell } from '@skeletonlabs/skeleton';
  import '../app.postcss';
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
	<slot />
</AppShell>


<!-- <div class="container h-full mx-auto flex justify-center items-center">
	<div class="space-y-5">
		<h1 class="h1">Let's get cracking bones!</h1>
		<p>Start by exploring:</p>
		<ul>
			<li><code class="code">/src/routes/+layout.svelte</code> - barebones layout</li>
			<li><code class="code">/src/app.postcss</code> - app wide css</li>
			<li>
				<code class="code">/src/routes/+page.svelte</code> - this page, you can replace the contents
			</li>
		</ul>
	</div>
</div> -->
