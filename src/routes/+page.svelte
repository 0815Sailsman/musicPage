<script>
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcome_fallback from '$lib/images/svelte-welcome.png';
</script>

<svelte:head>
	<title>Music page</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<div>
	<div class="content">
		Lorem Ipsum add content<br>
		Lorem Ipsum add content<br>
		Lorem Ipsum add content<br>
		Lorem Ipsum add content<br>
		Lorem Ipsum add content<br>
		Lorem Ipsum add content<br>
	</div>
	<div class="content">
		Lorem Ipsum add content<br>
		Lorem Ipsum add content<br>
		Lorem Ipsum add content<br>
		Lorem Ipsum add content<br>
		Lorem Ipsum add content<br>
		Lorem Ipsum add content<br>
	</div>
	<div class="content">
		Lorem Ipsum add content<br>
		Lorem Ipsum add content<br>
		Lorem Ipsum add content<br>
		Lorem Ipsum add content<br>
		Lorem Ipsum add content<br>
		Lorem Ipsum add content<br>
	</div>
	<div class="content">
		Lorem Ipsum add content<br>
		Lorem Ipsum add content<br>
		Lorem Ipsum add content<br>
		Lorem Ipsum add content<br>
		Lorem Ipsum add content<br>
		Lorem Ipsum add content<br>
	</div>
</div>

<style>
	.content {
		height: 60dvh;
		margin-bottom: 50px;
		background-color: hsl(var(--secondary));
	}
</style>