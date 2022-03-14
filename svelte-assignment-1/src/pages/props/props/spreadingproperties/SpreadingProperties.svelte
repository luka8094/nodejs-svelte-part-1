<script>

    import NestedSpreadingProperties from "./nestedspreadingproperties/NestedSpreadingProperties.svelte"

    const thePackage = {
        name : "ultra-Awesome-Super",
        version : 9000,
        speed : "mach speed",
        website : "https://svelte.dev"
    }

</script>

<section id="eleventh">

    <h3>11. Spreading properties exercise:</h3>    

    <NestedSpreadingProperties { ...thePackage}/>

</section>        

<style>

    h3{

        margin-right: auto;
    }

    #eleventh{
        display: flex;
        flex-direction: column;
        height: 200px;
        width: 60%;
        border: dashed 3px solid;
        justify-content: center;
        margin: auto;
    }

</style>