<script lang="ts">
	import { Carousel } from 'flowbite-svelte';
	import LineBreak from '$lib/components/Linebreak.svelte';
	import type { Image } from '$lib/types/index';

	let image: Image;

	const images = [
		{
			alt: 'Fall Retreat 2021',
			src: 'whoweare/fellowship/FallRetreat2021.jpg',
			description: 'Fall Retreat 2021'
		},
		{
			alt: 'New Member Installation 2019',
			src: 'whoweare/fellowship/NMI2019.jpg',
			description: 'New Member Installation 2019'
		},
		{
			alt: 'Snowcial 2020',
			src: 'whoweare/fellowship/Snowcial2020.jpg',
			description: 'Snowcial 2020'
		}
	];
</script>

<div>
	<div class="box">
		<div class="top-row">
			<div class="heading-text pb-4">
				<h1 class="size-xl">Fellowship</h1>
			</div>

			<div class="paintingcolor text-frame shadow text">
				<h2 class="size-md text-center font-bold p-4">
					“…Fellowship. The way we stay connected! Friendships everywhere, never endin! &#8211; Lay
					Hak, 19-20 Historian
				</h2>
				<p class="size-md text-center p-4">
					Our third and final tenet that we follow, Fellowship centers around, as you can guess, our
					social bonds and connections in Circle K. Members have the opportunity to make life long
					friendships and connections with their fellow club members, within the division, district,
					and even outside of Circle K in the form of other people under the Kiwanis umbrella or
					even people we meet along the way out in the real world.
				</p>
			</div>
		</div>

		<div class="bottom-row">
			<div class="py-4 m-auto">
				<div class="flex justify-center pb-7">
					<a
						href="/aboutfellowship"
						class="button px-6 pt-2.5 pb-2 text-white font-medium leading-normal rounded shadow-md hover:shadow-lg transition duration-500 ease-in-out flex align-center"
						>More about this tenet</a
					>
				</div>

				<div class="flex justify-center pb-4">
					<a
						href="/mentorshipprogram"
						class="button px-6 pt-2.5 pb-2 text-white font-medium leading-normal rounded shadow-md hover:shadow-lg transition duration-500 ease-in-out flex align-center"
						>Mentorship Program</a
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
