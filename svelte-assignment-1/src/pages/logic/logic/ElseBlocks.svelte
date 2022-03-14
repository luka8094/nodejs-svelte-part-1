<script>

    let user = { loggedIn : false }

    function toggleMeThisLogin(){
        user.loggedIn = !user.loggedIn
    }

</script>

<section id="thirteenth">

    <h3>13. Basic else... blocks exercise:</h3>

    {#if user.loggedIn}

        <button on:click={toggleMeThisLogin}>
        Log out
        </button>
    {:else}
        <button on:click={toggleMeThisLogin}>
        Log in
        </button>

    {/if}

</section>


<style>

h3{
        margin-right: auto;
    }

    #thirteenth{
        display: flex;
        flex-direction: column;
        height: 200px;
        width: 60%;
        border: dashed 3px solid;
        justify-content: center;
        margin: auto;
    }

    button{
        font-size: 1em;
        margin-right: auto;
    }

</style>