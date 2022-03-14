<script>

    const animals = [
        {id: 1, name : "cat"},
        {id: 2, name : "dog"},
        {id: 3, name : "kangaroo bob"}
    ]

</script>

<section id="fifteenth">

    <h3>15. Basic each blocks exercise:</h3>
    <p>Top 3 of worlds most loved animals</p>

    <ul>
        {#each animals as {id, name}, i}
            <li>{id} : {name}</li>
        {/each}
    </ul>

</section>

<style>

h3{
        margin-right: auto;
    }

    #fifteenth{
        display: flex;
        flex-direction: column;
        height: 200px;
        width: 60%;
        border: dashed 3px solid;
        justify-content: center;
        margin: auto;
    }

    ul{
        display: flex;
        flex-direction: column;
    }

    p, 
    li{
        font-size: 1em;
        margin-right: auto;
    }

</style>