<script>
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcome_fallback from '$lib/images/svelte-welcome.png';
</script>

<svelte:head>
	<title>Artyfind</title>
	<meta name="description" content="Description" />
</svelte:head>

<section>
	<picture>
		<source srcset={welcome} type="image/webp" />
		<img src={welcome_fallback} alt="Welcome" />
	</picture>
</section>

<style>
	img {
		display: none;
	}
</style>
