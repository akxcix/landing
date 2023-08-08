<script>
    import { goto } from '$app/navigation';
    
    export let text = 'Button'; // Default text
    export let onClick = () => {}; // Default click handler
    export let href = ''; // Default href
</script>
  
{#if href}
    <a class="btn" href={href} on:click|preventDefault={e => goto(href)}>{text}</a>
{:else}
    <button class="btn" on:click={onClick}>{text}</button>
{/if}

<style>
    .btn {
        margin: 5px;
        background-color: #121313;
        color: #EBEBEB;
        padding: 12px;
        text-decoration: none;
        border: 2px dashed #2C2C2C;
    }

    .btn:hover {
        background-color: #2C2C2C;
        color: #ebebeb;
    }
</style>
  