<script>

    import NestedEventForwarding from "./nestedeventforwarding/NestedEventForwarding.svelte"

    function pickingUpAnEventOverHere(event){

        alert(event.detail.text)

    }

</script>

<section id="twentifirst">

    <h3>21. Basic event forwarding exercise:</h3>

    <NestedEventForwarding on:message={pickingUpAnEventOverHere}/>

</section>
 
<style>

    h3{
        margin-right: auto;
    }
    
    #twentifirst{
        display: flex;
        flex-direction: column;
        height: 200px;
        width: 60%;
        border: dashed 3px solid;
        justify-content: center;
        margin: auto;
    }

</style>