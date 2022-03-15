<script>

    import NestedKeyedEachBlocks from "./nestedkeyedeachblocks/NestedKeyedEachBlocks.svelte"

    let animals = [
        {id: 1, name : "cat"},
        {id: 2, name : "dog"},
        {id: 3, name : "kangaroo bob"},
        {id: 4, name : "crabber"},
        {id: 5, name : "geeraph"}
    ]

    function removeAnAnimal(){
        animals = animals.slice(1)
    }

</script>

<section id="sixteenth">

    <h3>16. Keyed each blocks exercise:</h3>

    <button on:click={removeAnAnimal}>
    remove the first object
    </button>


    <div id="keyed-exercise-container">
        <div>
            <h2>This is the keyed part:</h2>
            {#each animals as animal (animal.id)}
                <NestedKeyedEachBlocks animalName={animal.name}/>
            {/each}

        </div>
        <div>
            <h2>This is the unkeyed part:</h2>
            {#each animals as animal}
                <NestedKeyedEachBlocks animalName={animal.name}/>
            {/each}

        </div>
    </div>

</section>

<style>

    h3,
    h2{
        margin-right: auto;
    }


    button{
        width: (150px - 35%);
    }

    #keyed-exercise-container{
        display: grid;
        grid-template-columns: 1fr 1fr;
        grid-gap: 1em;  
    }

    #sixteenth{
        display: flex;
        flex-direction: column;
        height: 500px;
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