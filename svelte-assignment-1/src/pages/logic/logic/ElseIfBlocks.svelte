<script>

    let randomNumber = Math.floor(Math.random() * 15) + 1

</script>

<section id="fourteenth">

    <h3>14. Basic if-else blocks exercise:</h3>

    {#if randomNumber === 15}
        <p>The number is too high!</p>
    {:else if randomNumber > 10 && randomNumber < 15}
        <p>The number is juuuust riiight.</p>
    {:else}
        <p>The number is lower than 10.</p>
    {/if}

</section>


<style>

h3{
        margin-right: auto;
    }

    #fourteenth{
        display: flex;
        flex-direction: column;
        height: 200px;
        width: 60%;
        border: dashed 3px solid;
        justify-content: center;
        margin: auto;
    }

    p{
        font-size: 1em;
        margin-right: auto;
    }

</style>