<script>
  import Card from "../../lib/components/Card.svelte";
  
  import {cardInfo} from "$lib/data.js";
</script>

<h3 class="text-center text-2xl p-4">List of Blog Categories</h3>
  <div class="w-[50%] m-auto p-4">
  <select class="select" size="4" value="1">
    <option value="1">Category 1</option>
    <option value="2">Category 2</option>
    <option value="3">Category 3</option>
    <option value="4">Category 4</option>
    <option value="5">Category 5</option>
  </select>
  </div>	

<section class="lg:grid grid-cols-2">
  {#each cardInfo as card}
    <Card {...card} />
  {/each}
</section>
