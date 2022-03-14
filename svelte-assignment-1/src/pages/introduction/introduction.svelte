<script>
  
    import HelloWorld from './introduction/HelloWorld.svelte'

    import DynamicAttributes from './introduction/DynamicAttributes.svelte'

    import Styling from './introduction/Styling.svelte'

    import Nested from './introduction/nested/Nested.svelte'

    import Html from './introduction/Html.svelte'

</script>

<div id="introduction-container">

    <HelloWorld/>
    <DynamicAttributes/>
    <Styling/>
    <Nested/>
    <Html/>

</div>

<style>

    #introduction-container{
        display: flex;
        flex-direction: column;
        height: 600px;
        background-color: lightyellow;
        width: calc(90% - 100px);
        margin: auto;
    }

</style>