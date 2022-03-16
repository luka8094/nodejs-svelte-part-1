<script>

    let m = { x : 0, y :0}

    function mousingOverTheDiv(event){
        m.x = event.clientX
        m.y = event.clientY
    }

</script>

<section id="seventeenth">

    <h3>17. Basic mouse event exercise:</h3>

    <div on:mousemove={mousingOverTheDiv}>

        The mouse at these coords : ({m.x} ,{m.y})

    </div>

</section>

<style>

    h3{
        margin-right: auto;
    }


    div{

        width: 400px;
        height: 300px;
        background-color: burlywood;

    }
    
    #seventeenth{
        display: flex;
        flex-direction: column;
        height: 200px;
        width: 60%;
        border: dashed 3px solid;
        justify-content: center;
        margin: auto;
    }

</style>