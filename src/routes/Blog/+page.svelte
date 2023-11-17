<script>
  import Card from "../../lib/components/Card.svelte";
  
  import {cardInfo} from "$lib/data.js";
</script>

<section class="lg:grid grid-cols-2">
  {#each cardInfo as card}
    <Card {...card} />
  {/each}
</section>

<!-- <section class="w-[50%] m-auto lg:grid grid-cols-2 p-4 pb-4 gap-4"></section>
 <div class="border-solid border-2 p-4 mb-4">  
    <h1>Blog Post 1</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente dolorum temporibus ipsa maxime impedit est facilis recusandae error harum suscipit iure molestias quasi quaerat commodi, ducimus magni dolor consequuntur ullam.</p>
  </div> 

  <div class="border-solid border-2 p-4 mb-4">
    <h1>Blog Post 2</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente dolorum temporibus ipsa maxime impedit est facilis recusandae error harum suscipit iure molestias quasi quaerat commodi, ducimus magni dolor consequuntur ullam.</p>
  </div>
  
  <div class="border-solid border-2 p-4 mb-4">
    <h1>Blog Post 3</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente dolorum temporibus ipsa maxime impedit est facilis recusandae error harum suscipit iure molestias quasi quaerat commodi, ducimus magni dolor consequuntur ullam.</p>
  </div>
  
  <div class="border-solid border-2 p-4 mb-4">
  <h1>Blog Post 4</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente dolorum temporibus ipsa maxime impedit est facilis recusandae error harum suscipit iure molestias quasi quaerat commodi, ducimus magni dolor consequuntur ullam.</p>
  </div>

  <div class="border-solid border-2 p-4 mb-4">
    <h1>Blog Post 5</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente dolorum temporibus ipsa maxime impedit est facilis recusandae error harum suscipit iure molestias quasi quaerat commodi, ducimus magni dolor consequuntur ullam.</p>
  </div>
  
  <div class="border-solid border-2 p-4 mb-4">
    <h1>Blog Post 6</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente dolorum temporibus ipsa maxime impedit est facilis recusandae error harum suscipit iure molestias quasi quaerat commodi, ducimus magni dolor consequuntur ullam.</p>
  </div>
  
</section> -->
