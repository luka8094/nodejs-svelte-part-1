<script>

    function onlyOneAlert(){
        alert('You\'ll only see this once!')
    }

</script>

<section id="nineteenth">

    <h3>19. Basic event modifiers exercise:</h3>

    <button on:click|once={onlyOneAlert}>
        clikeroo this button
    </button>

</section>

<style>

    h3{
        margin-right: auto;
    }


    button{

        width: 110px;
        height: 60px;
        color: white;
        background-color: orange;
        text-align: center;
        justify-content: center;
        align-items: center;

    }
    
    #nineteenth{
        display: flex;
        flex-direction: column;
        height: 200px;
        width: 60%;
        border: dashed 3px solid;
        justify-content: center;
        margin: auto;
    }

</style>