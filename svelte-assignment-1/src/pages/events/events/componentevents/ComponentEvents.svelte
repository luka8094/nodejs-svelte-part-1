<script>

    import NestedComponentEvents from "./nestedcomponentevents/NestedComponentEvents.svelte"

    function passMessage(event){

        alert(event.detail.text)

    }

</script>

<section id="twentienth">

    <h3>20. Basic component events exercise:</h3>

    <NestedComponentEvents on:message={passMessage}/>

</section>

<style>

    h3{
        margin-right: auto;
    }

    
    #twentienth{
        display: flex;
        flex-direction: column;
        height: 200px;
        width: 60%;
        border: dashed 3px solid;
        justify-content: center;
        margin: auto;
    }

</style>