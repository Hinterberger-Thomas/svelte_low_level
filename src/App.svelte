<script lang="ts">
	import * as api from "./util/api" 
	api.ledOn()
</script>

<main>
	<h1>this is just a test </h1>
	<button on:click = {() => console.log("hello")}></button>
</main>

<style>

</style>