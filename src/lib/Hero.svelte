<script>
  import BookingButton from "$lib/BookingButton.svelte";
</script>

<section class="hero-container">
  <h1 class="hero-text text">Healing Coast Chiropractic</h1>
  <h2 class="hero-descriptor text">
    Santa Cruz Chiropractor Specialized in Sports Performance, Injury Rehab, and
    Family + Pre-natal Care
  </h2>
  <h3 class="tagline text"><i>Do what you love without pain or injury</i></h3>
  <BookingButton />
  <div class="spacer" />
</section>

<style>
  .hero-container {
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    background: url("$lib/assets/sunsetbackgroundillustrated.jpg")
      rgba(255, 255, 255, 0.649);
    background-blend-mode: color;
    background-size: cover;
  }
  .hero-text {
    margin-top: 100px;
    font-size: 2.2rem;
  }
  .text {
    font-family: var(--font-primary);
  }

  .spacer {
    margin-top: 100px;
  }
</style>
