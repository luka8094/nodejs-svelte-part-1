<script>

    import { createEventDispatcher } from 'svelte'

    const dispatch = createEventDispatcher()

    function helloToYou(){
        dispatch('message' , { text : 'hello you there!'})
    }

</script>

<button on:click={helloToYou}>
    this button says hello to you!
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