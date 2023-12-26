<script lang="ts">
	import Pokecard from './../components/Pokecard.svelte';
    import Button from "../components/Button.svelte";

    let input: any;


</script>

<h1>Pokemon Card machine</h1>
<input type="text" name="pokemon" id="pok" bind:value={input}>
<Button />
<Pokecard />

<style>

</style>