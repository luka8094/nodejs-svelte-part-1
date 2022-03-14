<script>

    let someString = "world!"

</script>


<section id="first">

    <h3>1. Basic "Hello world" exercise:</h3>
    
    <p id="hello-world">Hello {someString}</p>

</section>

<style>

    h3{

        margin-right: auto;
    }

    #first{
        display: flex;
        flex-direction: column;
        height: 100px;
        width: 60%;
        border: dashed 3px solid;
        justify-content: center;
        margin: auto;
    }

    #hello-world{
        font-size: 1em;
        margin-right: auto;
    }

</style>