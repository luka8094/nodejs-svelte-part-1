<script>

    let user = { loggedIn : false }

    function toggleTheLogin(){
        user.loggedIn = !user.loggedIn
    }

</script>

<section id="twelth">

    <h3>12. Basic if... blocks exercise:</h3>


    {#if user.loggedIn}

        <button on:click={toggleTheLogin}>
            log out
        </button>

    {/if}

    {#if !user.loggedIn}

        <button on:click={toggleTheLogin}>
            sign in!
        </button>

    {/if}

</section>


<style>

h3{
        margin-right: auto;
    }

    #twelth{
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