<script>

    let count = 1;

    $: doubled = count * 2
    $: quadrupled = doubled * 2

    function handleThisCounter(){

        count += 1

    }


</script>

<section id="seventh">

    <h3>7. Basic "Hello world" exercise:</h3>
    
    <button id="click-button" on:click={handleThisCounter}>
        
       Count : {count}
    
    </button>

    <p>{count} * 2 = {doubled}</p>
    <p>{doubled} * 2 = {quadrupled}</p>

</section>

<style>

    h3{
        margin-right: auto;
    }

    #seventh{
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

    p{
        margin-right: auto;
    } 

</style>