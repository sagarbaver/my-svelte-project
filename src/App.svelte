<script>
	// export let name = "Sagar";
	import Surname from "./Surname.svelte";
	let myName = "Sagar";
</script>

<main>
	<h1>Hello {myName}!</h1>
	<Surname />
	<h3 class="headerText"> Welcome to your first Svelte app</h3>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
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

  .headerText {
    color: powderblue;
    font-family: "Comic Sans MS";
  }

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
