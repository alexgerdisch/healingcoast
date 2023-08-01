<script>
  import Nav from "$lib/Nav.svelte";
  import Footer from "$lib/Footer.svelte";
</script>

<Nav />
<slot />
<Footer />

<style>
  @font-face {
    font-family: "InstrumentSans";
    src: url("/fonts/InstrumentSans-variable.ttf");
  }
  :global(body) {
    margin: 0px;
  }

  :global(:root) {
    --button-primary: #d89279;
    --font-primary: "InstrumentSans";
  }
</style>
