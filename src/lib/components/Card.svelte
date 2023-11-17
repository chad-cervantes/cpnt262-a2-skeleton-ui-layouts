<script>
  //variables for cards
  export let title;
  export let description;
  export let url;
</script>

<!--format used for cards-->
  <article class="w-[60%] border-[2px] border-red-600 border-2 m-auto mb-4 p-4 pb-4 hover:opacity-75 transition ease-linear">
    <a href={url}>
      <h3 class="text-2xl text-center p-4">{title}</h3>
      <p class="text-md text-center">{description}</p>
    </a>
  </article>
		