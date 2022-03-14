<script>

    export let name
    export let version
    export let speed 
    export let website

</script>

<p id="spreadProperties">
    The download {speed} of this <code>{name}</code> package rox my sox!
    Download the newest version ({version}) from this place:
    <a href="https://www.npmjs.com/package/{name}">npm</a>. 
    More info <a href="{website}">here</a>.
</p>

<style>

    #spreadProperties{
        font-size: 1em;
        margin-right: auto;
    }

</style>