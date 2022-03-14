<script>

    let count = 0

    $: if(count >= 10 ){
        alert(`count is dangerously high!`)
        count = 9;
    }

    function handleThisStuff(){
        count += 1
    }


</script>

<section id="eighth">

    <h3>7. Basic "Hello world" exercise:</h3>
    
    <button id="click-button" on:click={handleThisStuff}>
        
       Clicked {count} {count === 1? 'time' : 'times'}
    
    </button>


</section>

<style>

    h3{
        margin-right: auto;
    }

    #eighth{
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