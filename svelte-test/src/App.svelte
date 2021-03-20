<script>
	let name = 'world-wide';
	let age = 134;
	function assign() {
		name = 'Azimut';
		age = 15;
	}
</script>

<h1>Hello {name}!</h1>

<h2 class={age < 84 ? 'active' : ''}>
	how old are you! { age }
</h2>

<img src="" alt={ name }/>

<input type="text" bind:value={ name }/>

<button on:click={ assign }>
	Assign
</button>
<style>
	h1 {
		color: red;
	}
	.active{
		color: blue;
	}
</style>