<script>
  let menuOpen = false;

  const toggleMenu = () => {
    if (menuOpen === false) {
      menuOpen = true;
    } else {
      menuOpen = false;
    }

    console.log(`Menu is open? ${menuOpen}`);
  };
</script>

<!-- svelte-ignore a11y-no-static-element-interactions -->
<!-- svelte-ignore a11y-click-events-have-key-events -->
<div
  id="toggle-button"
  class={menuOpen === true ? "opened" : "closed"}
  on:click={toggleMenu}
>
  <div class="toggle-piece" id="bar1" />
  <div class="toggle-piece" id="bar2" />
  <div class="toggle-piece" id="bar3" />
</div>

<section id="full-screen-menu">
  <ul id="menu-list">
    <li><a href="https://healingcoast.janeapp.com">Book Now</a></li>
    <li>Home</li>
    <li>About</li>
    <li>FAQ</li>
    <li>Contact</li>
    <ul />
  </ul>
</section>

<style>
  .toggle-piece {
    width: 60px;
    height: 10px;
    background-color: black;
    margin-top: 10px;
  }

  #full-screen-menu {
    display: none;
  }

  #menu-list {
    display: flex;
    flex-direction: column;
    align-items: center;
    list-style-type: none;
  }
</style>
