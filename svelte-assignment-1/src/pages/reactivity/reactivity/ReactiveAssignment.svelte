<script>

    let count = 0

    function handleThisAction(){
        
        count += 1

    }

</script>

<section id="sixth">

    <h3>6. Basic click button exercise:</h3>
    
    <button id="click-button" on:click={handleThisAction}>
        
        Clicked {count} { count === 0? "time" : "times"} 
    
    </button>

</section>

<style>

    h3{

        margin-right: auto;
    }

    #sixth{
        display: flex;
        flex-direction: column;
        height: 200px;
        width: 60%;
        border: dashed 3px solid;
        justify-content: center;
        margin: auto;
    }

    #click-button{
        font-size: 1em;
        margin-right: auto;
    }

</style>