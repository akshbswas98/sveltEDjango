<script>
    let film = 'The Usual Suspects'
</script>
<!-- <h1>{film.toUpperCase()}</h1> -->

{#if film.startsWith('T')}
    <p>Starts with 'T'</p>
{:else}
    <p>Doesn't starts with 'T'</p>
{/if}