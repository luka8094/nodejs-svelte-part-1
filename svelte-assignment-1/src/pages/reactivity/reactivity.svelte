<script>

    import ReactiveAssignment from './reactivity/ReactiveAssignment.svelte'

    import ReactiveDeclarations from './reactivity/ReactiveDeclarations.svelte'

    import ReactiveStatements from './reactivity/ReactiveStatements.svelte'

</script>


<div id="reactivity-container">

    <ReactiveAssignment/>
    <ReactiveDeclarations/>
    <ReactiveStatements/>

</div>

<style>

    #reactivity-container{
        display: flex;
        flex-direction: column;
        height: 600px;
        background-color: lightblue;
        width: calc(90% - 100px);
        margin: 10px auto 10px auto;
    }

</style>