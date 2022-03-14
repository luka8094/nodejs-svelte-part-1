<script>

    import NestedElement from "./NestedElement.svelte";

</script>


<section id="fourth">

    <h3>4. nested components exercise:</h3>
    
    <p>This styling does..</p>
    <NestedElement/>

</section>

<style>

    h3{

        margin-right: auto;
    }

    #fourth
    {
        display: flex;
        flex-direction: column;
        height: 100px;
        width: 60%;
        border: dashed 3px solid;
        justify-content: center;
        margin: auto;
    }

    p{
        color: magenta;
        font-family: 'comic sans', sans-serif;
        margin-right: auto;
    } 

</style>