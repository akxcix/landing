<script>
	import Button from "$lib/Button.svelte";
</script>

<footer>
    <Button href="https://github.com/wanderfusion" text="github" />
    <Button href="https://twitter.com/wanderfusion" text="twitter" />
</footer>
  

<style>
    footer {
        display: flex;
        justify-content: center;
        background-color: #121313;
        max-height: 5vh;
        padding: 12px;
        align-items: center;
        border-top: 2px dashed #2C2C2C;
    }
</style>