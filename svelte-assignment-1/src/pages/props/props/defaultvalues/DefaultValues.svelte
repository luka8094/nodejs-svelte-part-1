<script>

    import NestedDefaultValues from "./nesteddefaultvalues/NestedDefaultValues.svelte"

</script>

<section id="tenth">

    <h3>10. Declaring default values exercise:</h3>    

    <NestedDefaultValues someKindOfvalue={"it could be something!"}/>
    <NestedDefaultValues/>

</section>        

<style>

    h3{

        margin-right: auto;
    }

    #tenth{
        display: flex;
        flex-direction: column;
        height: 200px;
        width: 60%;
        border: dashed 3px solid;
        justify-content: center;
        margin: auto;
    }

</style>