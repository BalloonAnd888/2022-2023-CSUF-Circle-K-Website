<script>
	import { Carousel } from 'flowbite-svelte';
	import LineBreak from '$lib/components/Linebreak.svelte';
	const images = [
		{ alt: 'NMI', src: 'home/thegalleryslatest/NMI.png', description: '' },
		{
			alt: 'OpenMicNight',
			src: 'home/thegalleryslatest/OpenMicNight.jpg',
			description: ''
		},
		{
			alt: '3-2-1-Draw',
			src: 'home/thegalleryslatest/3-2-1-Draw!!!.jpg',
			description: ''
		},
		{
			alt: 'Snowcial',
			src: 'home/thegalleryslatest/CSUFSnowcial.gif',
			description: ''
		},
		{
			alt: 'CSUF7thSGM',
			src: 'home/thegalleryslatest/CSUF7thSGM.jpg',
			description: ''
		}
	];
</script>

<div>
	<h1 class="heading size-md text-white text-center font-bold underline pb-4">
		The Gallery's Latest
	</h1>

	<div class="gallery frame max-w-[700px]">
		<Carousel {images} imgClass="" duration={3900} let:Indicators let:Controls>
			<Controls />
			<Indicators />
		</Carousel>
	</div>

	<LineBreak />
</div>

<style>
	.gallery {
		margin: 0 15px;
	}

	.frame {
		border: 10px ridge #cccccc;
		background: #4c4c4c;
	}

	/*Small Tablet*/
	@media screen and (min-width: 620px) {
		.heading {
			font-size: var(--size-lg);
		}

		.gallery {
			margin: 0 150px;
		}
	}

	/*Large Tablet and Laptop*/
	@media screen and (min-width: 960px) {
		.heading {
			margin-bottom: 20px;
		}

		.gallery {
			margin: auto;
		}
	}

	/*Desktop*/
	@media screen and (min-width: 1200px) {
		.heading {
			margin-bottom: 40px;
		}

		.gallery {
			margin: auto;
		}
	}
</style>
