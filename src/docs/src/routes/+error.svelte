<script>
  import { page } from "$app/stores"
  import "$components/StyleHandler.svelte"
</script>

<div class="hero not-prose min-h-screen">
  <div class="hero-content text-center">
    <div class="max-w-md">
      <h1 class="mb-5 text-5xl font-bold opacity-10 lg:text-7xl xl:text-9xl">Error</h1>
      <p class="mb-5">{$page.error.message}</p>
      <a class="btn" href="/">Go back</a>
    </div>
  </div>
</div>
