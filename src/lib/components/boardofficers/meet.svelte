<script>
    import LineBreak from '$lib/components/linebreak.svelte';
</script>

<div class="background">
    <h1 class="text-white size-xl text-center animate__animated animate__fadeIn animate__slow">2022-2023 Board</h1>

    <!-- <div class="gallery px-4">
        <div id="carouselExampleCaptions" class="carousel slide relative" data-bs-ride="carousel">
            <div class="carousel-indicators absolute right-0 bottom-0 left-0 flex justify-center p-0 mb-4">
            <button
                type="button"
                data-bs-target="#carouselExampleCaptions"
                data-bs-slide-to="0"
                class="active"
                aria-current="true"
                aria-label="Slide 1"
            ></button>
            <button
                type="button"
                data-bs-target="#carouselExampleCaptions"
                data-bs-slide-to="1"
                aria-label="Slide 2"
            ></button>
            <button
                type="button"
                data-bs-target="#carouselExampleCaptions"
                data-bs-slide-to="2"
                aria-label="Slide 3"
            ></button>
            </div>

            <div class="carousel-inner relative w-full overflow-hidden">
            <div class="carousel-item active relative float-left w-full">
                <img
                src="https://mdbootstrap.com/img/Photos/Slides/img%20(15).jpg"
                class="block w-full"
                alt="..."
                />
                <div class="carousel-caption block absolute text-center">
                <h5 class="text-xl">First slide label</h5>
                </div>
            </div>

            <div class="carousel-item relative float-left w-full">
                <img
                src="https://mdbootstrap.com/img/Photos/Slides/img%20(22).jpg"
                class="block w-full"
                alt="..."
                />
                <div class="carousel-caption block absolute text-center">
                <h5 class="text-xl">Second slide label</h5>
                </div>
            </div>

            <div class="carousel-item relative float-left w-full">
                <img
                src="https://mdbootstrap.com/img/Photos/Slides/img%20(23).jpg"
                class="block w-full"
                alt="..."
                />
                <div class="carousel-caption block absolute text-center">
                <h5 class="text-xl">Third slide label</h5>
                </div>
            </div>
            </div>

            <button
            class="carousel-control-prev absolute top-0 bottom-0 flex items-center justify-center p-0 text-center border-0 hover:outline-none hover:no-underline focus:outline-none focus:no-underline left-0"
            type="button"
            data-bs-target="#carouselExampleCaptions"
            data-bs-slide="prev"
            >
            <span class="carousel-control-prev-icon inline-block bg-no-repeat" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
            </button>
            <button
            class="carousel-control-next absolute top-0 bottom-0 flex items-center justify-center p-0 text-center border-0 hover:outline-none hover:no-underline focus:outline-none focus:no-underline right-0"
            type="button"
            data-bs-target="#carouselExampleCaptions"
            data-bs-slide="next"
            >
            <span class="carousel-control-next-icon inline-block bg-no-repeat" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
            </button>
        </div>
    </div> -->

    <!-- <LineBreak /> -->
</div>

<style>
    h1 {
        padding: 30px 0;
    }

    /*Small Tablet*/ 
    @media screen and (min-width: 620px) {

    }

    /*Large Tablet and Laptop*/
    @media screen and (min-width: 960px) {
        .gallery {
            padding-left: 150px;
            padding-right: 150px;
        }
    }

    /*Desktop*/
    @media screen and (min-width: 1200px) {
        .gallery {
            padding-left: 300px;
            padding-right: 300px;
        }
    } 
</style>