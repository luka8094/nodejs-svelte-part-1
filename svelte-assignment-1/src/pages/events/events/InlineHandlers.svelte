<script>

    let m = { x : 0 , y : 0 }

</script>

<section id="eighteenth">

    <h3>18. Basic inline handlers exercise:</h3>

    <div on:mousemove={e => m = { x : e.clientX, y : e.clientY }}>

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
    
    #eighteenth{
        display: flex;
        flex-direction: column;
        height: 200px;
        width: 60%;
        border: dashed 3px solid;
        justify-content: center;
        margin: auto;
    }

</style>