<script>
	import Introduction from "./pages/introduction/Introduction.svelte"

	import Reactivity from "./pages/reactivity/Reactivity.svelte";

	import Props from "./pages/props/Props.svelte";

	import Logic from "./pages/logic/logic.svelte";

	import Events from "./pages/events/Events.svelte";

	let name = "there"
</script>

<main>
	<h1>Hello {name}!</h1>
	<p>Below are exercises from Svelte's homepage... check 'em out!</p>

	<Introduction/>
	<Reactivity/>
	<Props/>
	<Logic/>
	<Events/>

</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>