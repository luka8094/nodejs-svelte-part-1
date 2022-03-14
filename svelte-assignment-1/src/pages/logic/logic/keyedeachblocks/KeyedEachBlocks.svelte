<script>

    import NestedKeyedEachBlocks from "./nestedkeyedeachblocks/NestedKeyedEachBlocks.svelte"

    const animals = [
        {id: 1, name : "cat"},
        {id: 2, name : "dog"},
        {id: 3, name : "kangaroo bob"},
        {id: 4, name : "crabber"},
        {id: 5, name : "geeraph"}
    ]

</script>

<section id="sixteenth">

    <h3>16. Keyed each blocks exercise:</h3>

    <!--

    <ul>
        {#each animals as {id, name}, i}
            <li>{id} : {name}</li>
        {/each}
    </ul>

    -->

    <p>WIP</p>

</section>

<style>

h3{
        margin-right: auto;
    }

    #sixteenth{
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