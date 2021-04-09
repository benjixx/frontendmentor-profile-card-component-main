<script>
	import Profile from '$lib/Profile.svelte';
</script>

<main>
	<Profile />
</main>

<style>
	main {
		background: url(/bg-pattern-top.svg) -60vw -60vh no-repeat,
			url(/bg-pattern-bottom.svg) 60vw 60vh no-repeat, hsl(185, 75%, 39%);
		height: 100vh;
		padding: 50px;
	}
</style>
