<script>
  export let title;
  export let description;
  export let url;
</script>

<section class="border border-2 mb-4 mr-4 gap-4 p-4">
  <article class="w-[50%] m-auto p-4 pb-4 gap-4">
    <a href={url}>
      <h3 class="text-2xl">{title}</h3>
      <p class="text-l">{description}</p>
    </a>
  </article>
</section>