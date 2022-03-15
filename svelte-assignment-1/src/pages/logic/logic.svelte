<script>

    import IfBlocks from "./logic/IfBlocks.svelte"
    import ElseBlocks from "./logic/ElseBlocks.svelte"
    import ElseIfBlocks from "./logic/ElseIfBlocks.svelte"
    import EachBlocks from "./logic/EachBlocks.svelte"
    import KeyedEachBlocks from "./logic/keyedeachblocks/KeyedEachBlocks.svelte"

</script>


<div id="logic-container">

    <IfBlocks/>
    <ElseBlocks/>
    <ElseIfBlocks/>
    <EachBlocks/> 
    <KeyedEachBlocks/>

</div>

<style>

    #logic-container{
        display: flex;
        flex-direction: column;
        height: 1200px;
        background-color: lightgreen;
        width: calc(90% - 100px);
        margin: 10px auto 10px auto;
    }

</style>