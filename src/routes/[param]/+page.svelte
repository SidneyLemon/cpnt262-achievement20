<script>
  import { page } from "$app/stores";
  console.log($page.param);
</script>

<main>
  <h1>{$page.params.param}</h1>
</main>
