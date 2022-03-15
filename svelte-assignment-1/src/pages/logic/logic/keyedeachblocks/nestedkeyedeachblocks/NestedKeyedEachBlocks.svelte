<script>

    export let animalName

</script>

<p>
    <span>{animalName}</span>
    <span>{animalName}</span>
</p>

<style>

    p{
        display: flex;
    }

    span{
        display: flex;
        height: 30px;
        width: 70px;
        align-items: center;
        justify-content: center;
        border: dashed 2px black;
    }


</style>