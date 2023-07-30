<script>
    import Logo from "$lib/Logo.svelte";
    import Menu from "$lib/Menu.svelte";
    import BookingButton from "$lib/BookingButton.svelte";
</script>

<nav>
    <Menu/>
    
    <Logo/>

    <BookingButton/>
    
</nav>



<style>
    nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
        background-color: orange;
    }
</style>