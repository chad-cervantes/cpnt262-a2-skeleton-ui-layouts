<script>
  import { AppShell } from "@skeletonlabs/skeleton";
</script>

<slot />

<AppShell>
  <svelte:fragment slot="footer">
    <div class="text-center p-4">
      &copy; 2023 Chad Cervantes
    </div>
  </svelte:fragment>
</AppShell>
