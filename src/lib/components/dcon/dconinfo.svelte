<script lang="ts">
	import { Carousel } from 'flowbite-svelte';
	import type { Image } from '$lib/types/index';

	let image: Image;

	const images = [
		{
			alt: 'DCONHR',
			src: 'src/lib/images/leadership/dcon/DCONHR.jpg',
			description: 'DCONHR'
		},
		{
			alt: 'DCONPE',
			src: 'src/lib/images/leadership/dcon/DCONPE.jpg',
			description: 'DCONPE'
		},
		{
			alt: 'DCONSAA',
			src: 'src/lib/images/leadership/dcon/DCONSAA.jpg',
			description: 'DCONSAA'
		},
		{
			alt: 'DCONTSCN',
			src: 'src/lib/images/leadership/dcon/DCONTSCN.jpg',
			description: 'DCONTSCN'
		}
	];
</script>

<div class="text-white">
	<h1 class="size-xl text-center animate__animated animate__fadeIn animate__slow">
		District Convention
	</h1>

	<p class="description size-md px-5 m-auto">
		Rivaled only in size by Fall Training Conference, District Convention is an annual event where
		Circle K'ers from all over the CNH Circle K District gather together over three days, two nights
		to learn more about all levels of Circle K International, educate themselves about how to become
		more inspiring leaders, and, most importantly, celebrate a year's worth of hard-work and
		accomplishments!
	</p>

	<div class="animate__animated animate__fadeInLeft pt-4">
		<img
			src="src/lib/images/leadership/dcon/dcon2022.jpg"
			class="frame shadow w-[500px] mb-4 mx-auto lg:hover:scale-110 transition duration-300 ease-in-out"
			alt="ftc2021"
		/>
	</div>

	<div class="pb-6">
		<h2 class="size-xl text-center">Basic Information</h2>

		<div class="size-md text-center px-5">
			<ul class="inline-block text-left">
				<li>Where: Marriot Convention Center - Riverside at Riverside, CA</li>
				<li>When: 3/24-3/26</li>
				<li>Cost: $259</li>
			</ul>
		</div>
	</div>

	<div class="pb-6">
		<h2 class="size-xl text-center">Important Dates & Deadlines</h2>

		<div class="size-md text-center">
			<ul class="inline-block text-left">
				<li>3/10: Registration</li>
				<li>3/10: Professional Expo</li>
				<li>3/17: SAA Form</li>
				<li>3/17: Talent Show x Culture Night</li>
			</ul>
		</div>
	</div>

	<div class="list pb-6">
		<div class="p-4 animate__animated animate__fadeIn animate__slow">
			<a
				href="https://docs.google.com/forms/d/e/1FAIpQLSdEK5I-9E-yV6xO1ErtAwmhWSLWCcQ4FUqrITDngs7bTm4fZQ/viewform?fbclid=IwAR2yglqFsmQG_iJbNGTDCjhmEMtxFDm2k31DY-lniOaAfNsLFDGxIbm0GQg"
				target="_blank"
				class="button rounded shadow-md hover:shadow-lg active:shadow-lg transition duration-500 ease-in-out"
				>Registration Form</a
			>
		</div>

		<div class="p-4 animate__animated animate__fadeIn animate__slow">
			<a
				href="https://docs.google.com/document/d/1nS0Wcy4-JD2eKOtofZ8PPYhuVquYLV4IW78-woarXA8/edit?fbclid=IwAR01HgjUXTnlPPCOCrsRlJ4iGNwegzDfi6RmNWp-QalneKf-t8cttI35Wac"
				target="_blank"
				class="button rounded shadow-md hover:shadow-lg active:shadow-lg transition duration-500 ease-in-out"
				>Attendance Agreement Form</a
			>
		</div>

		<div class="p-4 animate__animated animate__fadeIn animate__slow">
			<a
				href="https://docs.google.com/document/d/1x_MWyzlfdcD8rawhW-nP8-OrVN-Yvl_MgMFFfuUv4rw/edit?fbclid=IwAR26lmVZkkSk9F0OZvkjU8yEMWFhs0UuySsPOnVcf8AVCiB7oTPUmm00IIU"
				target="_blank"
				class="button rounded shadow-md hover:shadow-lg active:shadow-lg transition duration-500 ease-in-out"
				>Code of Conduct</a
			>
		</div>

		<div class="p-4 animate__animated animate__fadeIn animate__slow">
			<a
				href="https://docs.google.com/document/d/1WG6xO8MU84yRXfgFE0KIeASasQkgXI1WkDsIiGTSCNE/edit?fbclid=IwAR1gRMyv6gKLzYI3s7ko55zz-Bfhq6z5Hu7jEBxSgob9jwb__KVNDBTcI2E"
				target="_blank"
				class="button rounded shadow-md hover:shadow-lg active:shadow-lg transition duration-500 ease-in-out"
				>Release of Liability</a
			>
		</div>

		<div class="p-4 animate__animated animate__fadeIn animate__slow">
			<a
				href="https://docs.google.com/forms/d/e/1FAIpQLSdJcJPFkb-cfjudkom1ix8dZjbGtH-mb_LaILuTvKn9oMKudg/viewform"
				target="_blank"
				class="button rounded shadow-md hover:shadow-lg active:shadow-lg transition duration-500 ease-in-out"
				>DCON SAA Sign-up</a
			>
		</div>

		<div class="p-4 animate__animated animate__fadeIn animate__slow">
			<a
				href="https://docs.google.com/document/d/1Nioce9ijBwyCT216Mrk7tb1CaGPr8GII6GL3Aef6sG0/edit"
				target="_blank"
				class="button text-xs rounded shadow-md hover:shadow-lg active:shadow-lg transition duration-500 ease-in-out"
				>DCON Talent Show x Culture Night Sign-up</a
			>
		</div>

		<div class="p-4 animate__animated animate__fadeIn animate__slow">
			<a
				href="https://docs.google.com/forms/d/e/1FAIpQLScmUJNN--aupE0qkEi7G27q8m0WO1N4MtM0lCPKLu9Kcnuf8g/viewform"
				target="_blank"
				class="button rounded shadow-md hover:shadow-lg active:shadow-lg transition duration-500 ease-in-out"
				>Professional Expo Interest Form</a
			>
		</div>
	</div>

	<div class="pb-5">
		<div class="gallery frame">
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
		</div>
	</div>
</div>

<style>
	h1 {
		padding: 30px 0;
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

	.gallery {
		margin: 0 15px;
	}

	.button {
		display: block;
		color: white;
		font-weight: 500;
		font-size: var(--size-sm);
		background-color: #babcc9;
		padding: 19px 0;
		height: 64px;
		max-width: 250px;
		text-align: center;
		margin: auto;
	}

	.button:hover {
		background-color: #e3edf2;
		color: black;
	}

	/*Small Tablet*/
	@media screen and (min-width: 620px) {
		.description {
			padding: 0 50px;
		}
	}

	/*Large Tablet and Laptop*/
	@media screen and (min-width: 960px) {
		.description {
			padding: 0 80px;
		}

		.gallery {
			margin: 0 150px;
		}

		.button {
			width: 250px;
		}
	}

	/*Desktop*/
	@media screen and (min-width: 1200px) {
		.description {
			padding: 0 200px;
		}

		.gallery {
			margin: 0 250px;
		}
	}
</style>
