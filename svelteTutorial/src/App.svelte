<script>
	let count = 0;
	$: doubled = count * 2;

	$: if (count >= 10) {
		console.log(`the count is ${count}`);
		alert(`I said the count is ${count}`);
		count = 10;
	}
	function handleClick() {
		count += 1;
	}
</script>

<button on:click={handleClick}>
	Clicked {count} {count === 1 ? 'time' : 'times'}
</button>
<p>{count} doubled is {doubled}</p>