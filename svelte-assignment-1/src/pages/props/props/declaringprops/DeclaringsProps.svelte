<script>

    import NestedDeclaringProps from './nesteddeclaringprops/NestedDeclaringProps.svelte'


</script>

<section id="nineth">

    <h3>9. Declaring properties exercise:</h3>    

        <NestedDeclaringProps someKindOfAnswer={"working"}/>

</section>        

<style>

    h3{

        margin-right: auto;
    }

    #nineth{
        display: flex;
        flex-direction: column;
        height: 200px;
        width: 60%;
        border: dashed 3px solid;
        justify-content: center;
        margin: auto;
    }


</style>