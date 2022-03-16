<script>

    import { createEventDispatcher } from 'svelte' 

    const eventDispatcher = createEventDispatcher()

    function letsSayHelloAgain(){

        eventDispatcher('message' , { text : "hello again!"})

    }

</script>

<button on:click={letsSayHelloAgain}>
    Imma tellya hi
</button>

<style>

    button{

        width: 110px;
        height: 60px;
        color: white;
        background-color: orange;
        text-align: center;
        justify-content: center;
        align-items: center;

    }

</style>