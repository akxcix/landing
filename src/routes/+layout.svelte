<script>
    import Nav from "$lib/Nav.svelte";
    import Footer from "$lib/Footer.svelte";
    import '../global.css';
</script>


<Nav />
<main>
    <slot />
</main>
<Footer />


<style>
    main {
        /* display: flex;
        flex-direction: column;
        flex-direction: column;
        align-items: center;
        min-height: 85vh; */

        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        /* min-height: 100vh; */
        padding: 40px 20px;
        /* max-width: 900px; */
        margin-left: 5vh;
        margin-right: 5vh;
        border-left: 2px dashed #2C2C2C;
        border-right: 2px dashed #2C2C2C;
    }
</style>
