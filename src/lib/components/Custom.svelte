<script>
let lists = [
    { id: 1, title: 'Lorem Ipsum 1' },
    { id: 2, title: 'Lorem Ipsum 2' },
    { id: 3, title: 'Lorem Ipsum 3' },
    { id: 4, title: 'Lorem Ipsum 4' },
    { id: 5, title: 'Lorem Ipsum 5' },
  ];

</script>

<section class="text-center text-xl p-4 tracking-wide strong">
	{#each lists as list (list.id)}
		<list id={list.id}>{list.title}</list>
	{/each}
</section>

<h3 class="text-center text-2xl">List</h3>
<div class="w-[50%] m-auto">
<select class="select" size="4" value="1">
	<option value="1">{lists.title}</option>
	<option value="2">{lists.title}</option>
	<option value="3">{lists.title}</option>
	<option value="4">{lists.title}</option>
	<option value="5">{lists.title}</option>
</select>
</div>					