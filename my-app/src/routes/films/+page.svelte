<script>
    let films = [
        { id: 1, name: 'The Godfather', director: 'William da'},
        { id: 1, name: 'Leon the Professional', director: 'Micheal da'}
    ]
</script>

<ul>
    {#each films as film}
        <li>
            <a href="films/{film.id}">{film.name}</a>
        </li>
    {/each}

    </ul>