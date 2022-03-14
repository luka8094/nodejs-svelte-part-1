<script>

    import DeclaringsProps from './props/declaringprops/DeclaringsProps.svelte'
    import DefaultValues from './props/defaultvalues/DefaultValues.svelte'
    import SpreadingProperties from './props/spreadingproperties/SpreadingProperties.svelte'

</script>


<div id="props-container">

    <DeclaringsProps/>
    <DefaultValues/>
    <SpreadingProperties/>

</div>

<style>

    #props-container{
        display: flex;
        flex-direction: column;
        height: 600px;
        background-color: lightcyan;
        width: calc(90% - 100px);
        margin: 10px auto 10px auto;
    }

</style>