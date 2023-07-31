<script>
	import { onMount } from 'svelte';

	onMount(() => {});
</script>

<div class="background" />
<div class="overlay">
	<div class="container text-wrap">
		<h1 class="text-center h1">Path of Exile 2 Wiki</h1>
		<p class="text-center">
			Welcome to the Path of Exile 2 Wiki. This is a fan-made wiki for the upcoming game Path of
			Exile 2. <br /> This wiki is currently a work in progress and will be updated as more information
			is released.
		</p>
		<p class="text-center mt-12">
			In the meantime, you can check out the{' '}
			<a
				href="https://www.poewiki.net/wiki/Path_of_Exile_2"
				target="_blank"
				class="btn btn-sm variant-ghost-primary"
				rel="noopener noreferrer"
				>Path of Exile 2 page
			</a> on PoEWiki.net
		</p>

		<p class="text-center mt-4">
			You can also visit the PoEWiki{' '}
			<a
				class="btn btn-sm variant-ghost-tertiary"
				href="https://discord.gg/CE46HADc5T"
				target="_blank"
				rel="noreferrer"
			>
				Discord
			</a>
			server
		</p>

		<p class="text-center mt-4">
			Fork Fandom! {' '}
			<a
				class="btn btn-sm variant-ghost-surface"
				href="https://forkfandom.com/"
				target="_blank"
				rel="noreferrer">Read More</a
			>
		</p>

		<!-- add a footnote saying we are not affiliated with GGG -->
		<div class="bottom">
			<p class="text-center">
				This product isn't affiliated with or endorsed by Grinding Gear Games in any way.
			</p>
		</div>
	</div>
</div>

<style lang="postcss">
	.background {
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
		background-image: url('/backgrounds/background1.png');
		background-repeat: no-repeat;
		background-size: cover;
		background-position: center;
	}

	.overlay {
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
		background-color: rgba(0, 0, 0, 0.6);
		display: flex;
		align-items: center;
		justify-content: center;
	}

	.text-wrap {
		max-width: 800px;
	}

	.bottom {
		position: absolute;
		bottom: 0;
		left: 0;
		width: 100%;
	}
</style>
