<script>
  import Nav from "$lib/Nav.svelte";
  import Footer from "$lib/Footer.svelte";
</script>

<Nav />
<slot />
<Footer />

<style>
  :global(body) {
    margin: 0px;
  }

  :global(:root) {
    --button-primary: #d89279;
  }
</style>
