<script lang="ts">
	import { Carousel } from 'flowbite-svelte';
	import LineBreak from '$lib/components/Linebreak.svelte';
	import type { Image } from '$lib/types/index';

	let image: Image;

	const images = [
		{
			alt: 'Light The Night',
			src: 'whoweare/service/LightTheNight.jpg',
			description: 'Light The Night'
		},
		{
			alt: 'El Modena',
			src: 'whoweare/service/ElMo.jpg',
			description: 'El Modena'
		},
		{
			alt: '24 Hour Service Marathon',
			src: 'whoweare/service/24hrService.jpg',
			description: '24 Hour Service Marathon'
		}
	];
</script>

<div>
	<div class="box animate__animated animate__fadeInLeft">
		<div class="top-row">
			<div class="heading-text pb-4">
				<h1 class="size-xl">Service</h1>
			</div>

			<div class="paintingcolor text-frame shadow text">
				<h2 class="size-md text-center font-bold p-4">
					“…our first tenet that we follow. Givin back to our community today not tomorrow…”
				</h2>
				<p class="size-md text-center p-4">
					The first and most fundamental tenet of Circle K International is Service. Through
					Service, we strive to make our communities and the world a better place, one service
					project at a time. Here at CSUF Circle K, we provided all our members many opportunities
					to leave their mark and make a difference in their communities.
				</p>
			</div>
		</div>

		<div class="bottom-row">
			<div class="py-4 m-auto">
				<div class="flex justify-center pb-7">
					<a
						href="/aboutservice"
						class="button px-6 pt-2.5 pb-2 text-white font-medium leading-normal rounded shadow-md hover:shadow-lg transition duration-500 ease-in-out flex align-center"
						>More about this tenet</a
					>
				</div>

				<div class="flex justify-center pb-4">
					<a
						href="/calendar"
						class="button px-6 pt-2.5 pb-2 text-white font-medium leading-normal rounded shadow-md hover:shadow-lg transition duration-500 ease-in-out flex align-center"
						>Calendar</a
					>
				</div>
			</div>

			<div class="gallery gallery-frame shadow">
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
	<LineBreak />
</div>

<style>
	.heading-text {
		color: white;
		display: flex;
		justify-content: center;
		align-items: center;
		font-weight: 700;
		text-align: center;
		text-decoration: underline;
	}

	.button {
		font-size: var(--size-sm);
		background-color: #babcc9;
	}

	.button:hover {
		background-color: #e3edf2;
		color: black;
	}

	.text-frame {
		border: 10px ridge #cccccc;
		margin: 0 24px 20px 24px;
	}

	.shadow {
		box-shadow:
			0px 10px 13px -7px #000000,
			10px 12px 11px 4px rgba(0, 0, 0, 0);
	}

	.gallery {
		margin: 0 10px;
	}

	.gallery-frame {
		border: 10px ridge #cccccc;
		background: #4c4c4c;
		margin: 0 24px 20px 24px;
	}

	.paintingcolor {
		background-color: #f0f0d8;
	}

	.text {
		color: black;
	}

	/*Small Tablet*/
	@media screen and (min-width: 620px) {
		.text-frame {
			margin: 0 50px 20px 50px;
		}

		.gallery-frame {
			margin: 0 50px;
		}
	}

	/*Large Tablet and Laptop*/
	@media screen and (min-width: 960px) {
		.box {
			display: flex;
			flex-wrap: wrap;
			margin: 0 100px;
		}

		.top-row {
			display: inline-flex;
			width: 100%;
			padding-bottom: 50px;
		}

		.top-row div {
			width: 50%;
			height: 100%;
			float: left;
		}

		.bottom-row {
			display: inline-flex;
			flex-direction: row-reverse;
			width: 100%;
			justify-content: space-between;
		}

		.gallery {
			padding: 0px;
			margin: 0px;
			width: 50%;
			height: 100%;
			float: left;
		}

		.text-frame {
			margin: 0 0 20px 50px;
		}
	}

	/*Desktop*/
	@media screen and (min-width: 1200px) {
		.gallery-frame {
			margin: 0 0 0 100px;
		}

		.text-frame {
			margin: 0 100px 20px 0px;
		}

		.button {
			font-size: var(--size-md);
		}
	}
</style>
