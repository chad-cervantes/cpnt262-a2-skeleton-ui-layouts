<script>
  import { AppShell } from '@skeletonlabs/skeleton';
  import { ListBox, ListBoxItem } from '@skeletonlabs/skeleton';
  let valueSingle = 'books';
</script>


<AppShell>
	<svelte:fragment slot="header">
    <div class="text-5xl text-center p-4">
      Lorem Ipsum
    </div>
  </svelte:fragment>
	<svelte:fragment slot="sidebarLeft">
    <div class="sm:text-sm overflow-x-hidden overflow-y-auto p-4 w-[85%] m-auto">
      <h1 class="text-center text-2xl p-4">Categories</h1>
      <ListBox>
        <ListBoxItem bind:group={valueSingle} name="medium" value="books">Costumes</ListBoxItem>
        <ListBoxItem bind:group={valueSingle} name="medium" value="movies">Decorations</ListBoxItem>
        <ListBoxItem bind:group={valueSingle} name="medium" value="tv">Themes</ListBoxItem>
        <ListBoxItem bind:group={valueSingle} name="medium" value="mobile">Colors</ListBoxItem>
      </ListBox>
		</div>	
 </svelte:fragment>
	<svelte:fragment slot="pageHeader">
    <div class="text-2xl text-center p-4">
      November Posts
    </div>
  </svelte:fragment>
	<slot />
</AppShell>