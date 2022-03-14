<script>

    let src = "./images/early-internet-smiley.gif" 

    let name = "a name"

</script>


<section id="second">

    <h3>2. basic image exercise:</h3>
    
    <img id="image" {src} alt="{name}"/>

</section>

<style>

    h3{

        margin-right: auto;
    }

    #second{
        display: flex;
        flex-direction: column;
        height: 100px;
        width: 60%;
        border: dashed 3px solid;
        justify-content: center;
        margin: auto;
    }

    #image{
        font-size: 1em;
        margin-right: auto;
    }

</style>