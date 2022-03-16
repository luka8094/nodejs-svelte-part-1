<script>

    import DomEvents from "./events/DomEvents.svelte"
    import InlineHandlers from "./events/InlineHandlers.svelte"
    import EventModifiers from "./events/EventModifiers.svelte"
    import ComponentEvents from "./events/componentevents/ComponentEvents.svelte"
    import EventForwarding from "./events/eventforwarding/EventForwarding.svelte"

</script>


<div id="events-container">

    <DomEvents/>
    <InlineHandlers/>
    <EventModifiers/>
    <ComponentEvents/>
    <EventForwarding/>

</div>

<style>

    #events-container{
        display: flex;
        flex-direction: column;
        height: fit-content;
        background-color: lightcyan;
        width: calc(90% - 100px);
        margin: 10px auto 10px auto;
    }

</style>