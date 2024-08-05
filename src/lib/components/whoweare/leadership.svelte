<script lang="ts">
	import { Carousel } from 'flowbite-svelte';
	import LineBreak from '$lib/components/Linebreak.svelte';
	import type { Image } from '$lib/types/index';

	let image: Image;

	const images = [
		{
			alt: 'Discoverfest Spring 2020',
			src: 'whoweare/leadership/DfestSp2020.jpg',
			description: 'Discoverfest Spring 2020'
		},
		{
			alt: 'Family Head 2019',
			src: 'whoweare/leadership/Famhead19.jpg',
			description: 'Family Head 2019'
		},
		{
			alt: 'District Convention 2022',
			src: 'whoweare/leadership/DCON22.jpg',
			description: 'District Convention 2022'
		}
	];
</script>

<div>
	<div class="box">
		<div class="top-row">
			<div class="heading-text pb-4">
				<h1 class="size-xl">Leadership</h1>
			</div>

			<div class="paintingcolor text-frame shadow text">
				<h2 class="size-md text-center font-bold p-4">
					“…Leadership! Is also something we like to do. Givin all our members the chance to lead
					the crew…”
				</h2>
				<p class="size-md text-center p-4">
					Everybody can be a leader! And we mean that truly. Our second tenet that we follow, CSUF
					Circle K aims to grow and develop the leadership skills of every one of our members,
					whether it be through serving as a Board Officer, serving on a committee &nbsp;&#40;club,
					divisional, district&#41;, or even chairing an event.
				</p>
			</div>
		</div>

		<div class="bottom-row">
			<div class="py-4 m-auto">
				<div class="flex justify-center pb-7">
					<a
						href="/aboutleadership"
						class="button px-6 pt-2.5 pb-2 text-white font-medium leading-normal rounded shadow-md hover:shadow-lg transition duration-500 ease-in-out flex align-center"
						>More about this tenet</a
					>
				</div>

				<div class="flex justify-center pb-4">
					<a
						href="/boardofficers"
						class="button px-6 pt-2.5 pb-2 text-white font-medium leading-normal rounded shadow-md hover:shadow-lg transition duration-500 ease-in-out flex align-center"
						>22-23 Board</a
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

<!-- 
    Discoverfest Spring 2020
    Family Head 2019-2020
    District Convention 2022
 -->

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
