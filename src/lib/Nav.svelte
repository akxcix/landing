<script>
    import Button from "$lib/Button.svelte";
</script>

<nav>
    <a href="/"><img src="/logo.png" alt="wanderfusion logo" class="logo"></a>
    <Button href="https://app.wanderfusion.com" text="Go to App"/>
</nav>

<style>
    nav {
        display: flex;
        justify-content: space-between;
        background-color: #121313;
        padding: 12px;
        align-items: center;
        border-bottom: 2px dashed #2C2C2C;
        max-height: 5vh;
    }

    .logo {
        max-height: 40px;
        width: auto;
    }
</style>
  