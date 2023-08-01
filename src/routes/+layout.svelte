<script>
  import Nav from "$lib/Nav.svelte";
  import Footer from "$lib/Footer.svelte";
</script>

<Nav />
<slot />
<Footer />

<style>
  @font-face {
    font-family: "TenorSans";
    src: url("/fonts/TenorSans-Regular.ttf");
  }
  :global(body) {
    margin: 0px;
  }

  :global(:root) {
    --button-primary: #d89279;
    --font-primary: "TenorSans";
  }
</style>
