<script>
	let title = 'Jessicas Super Cool Website';

	const updateTitle = () => {
		title = 'Maybe its not so cool after all';
	};
</script>

<div class="index">
	<h2>{title}</h2>
	<p>
		Lorem, ipsum dolor sit amet consectetur adipisicing elit. Suscipit incidunt repellendus totam
		vel illo voluptatum maxime. Inventore necessitatibus ex magnam harum ab quae aut quod. Pariatur
		asperiores quos nihil id, deleniti accusantium atque necessitatibus mollitia suscipit adipisci
		illum sit repudiandae quia magnam quas error libero, eum explicabo! Asperiores, dolorem
		provident.
	</p>
	<button on:click={updateTitle} />
	<input type="text" bind:value={title} />
</div>

<style>
	.index {
		text-align: center;
		display: block;
		margin: 20px auto;
	}
</style>
