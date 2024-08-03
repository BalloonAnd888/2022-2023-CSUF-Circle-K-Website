<script lang="ts">
	import { Carousel } from 'flowbite-svelte';
	import type { Image } from '$lib/types/index';

	let image: Image;

	const images = [
		{
			alt: 'Snowcial 2020',
			src: 'src/lib/images/fellowship/snowcial.jpg',
			description: 'Snowcial 2020'
		},
		{
			alt: 'Family Competition',
			src: 'src/lib/images/fellowship/familycomp.jpg',
			description: 'Family Competition'
		}
	];
</script>

<div>
	<h1 class="text-white size-lg text-center pb-10">Fellowship Events</h1>

	<div class="box">
		<div class="gallery frame shadow">
			<Carousel
				{images}
				imgClass=""
				duration={3900}
				let:Indicators
				let:Controls
				on:change={({ detail }) => (image = detail)}
			>
				<Controls />
				<Indicators />
			</Carousel>

			<div class="rounded h-10 bg-gray-300 dark:bg-gray-700 dark:text-white p-2 my-2 text-center">
				{image?.description}
			</div>
		</div>
	</div>
</div>

<style>
	.box {
		padding: 0 20px 20px 20px;
	}

	.gallery {
		margin: auto;
	}

	.frame {
		border: 10px ridge #cccccc;
		background: #4c4c4c;
	}

	.shadow {
		box-shadow:
			0px 10px 13px -7px #000000,
			10px 12px 11px 4px rgba(0, 0, 0, 0);
	}

	/*Small Tablet*/
	@media screen and (min-width: 620px) {
		.box {
			padding: 0 50px 40px 50px;
		}
	}

	/*Large Tablet and Laptop*/
	@media screen and (min-width: 960px) {
		.box {
			padding: 0 80px 70px 80px;
		}
	}

	/*Desktop*/
	@media screen and (min-width: 1200px) {
		.box {
			padding: 0 200px 100px 200px;
		}
	}
</style>
