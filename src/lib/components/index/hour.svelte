<script>
    import LineBreak from '$lib/components/linebreak.svelte';
</script>

<div>
    <h1 class="heading px-8 pb-4 font-bold underline" data-aos="fade" data-aos-once="true" data-aos-anchor-placement="top-bottom" data-aos-duration="2100">
        Total Hours &nbsp;&#40;As of February&#41;
    </h1>

    <div class="list container m-auto grid grid-cols-1 lg:grid-cols-3">
        <div class="lg:gap-8 lg:hover:scale-110 transition duration-300 ease-in-out">
            <div class="hour px-14 pb-4 text-center"  data-aos="fade" data-aos-once="true" data-aos-anchor-placement="top-bottom" data-aos-duration="2000">
                <div class="frame col-span-1 flex flex-col shadow-lg">
                    <h5 class="text-black font-medium">Service</h5>
                    <p>2046.5</p>
                </div>
            </div>
        </div>

        <div class="lg:gap-8 lg:hover:scale-110 transition duration-300 ease-in-out">
            <div class="hour px-14 pb-4 text-center"  data-aos="fade" data-aos-once="true" data-aos-anchor-placement="top-bottom" data-aos-duration="2000">
                <div class="frame col-span-1 flex flex-col shadow-lg">
                    <h5 class="text-black font-medium">Leadership</h5>
                    <p>2969</p>
                </div>
            </div>
        </div>

        <div class="lg:gap-8 lg:hover:scale-110 transition duration-300 ease-in-out">
            <div class="hour px-14 pb-4 text-center"  data-aos="fade" data-aos-once="true" data-aos-anchor-placement="top-bottom" data-aos-duration="2000">
                <div class="frame col-span-1 flex flex-col shadow-lg">
                    <h5 class="text-black font-medium">Fellowship</h5>
                    <p>3915.5</p>
                </div>
            </div>
        </div>
    </div>

    <LineBreak />
</div>

<style>
    .heading {
        color: white;
        text-align: center;
        font-size: var(--size-md);
    }

    .hour {
        font-size: var(--size-md);
        text-align: center;
    }

    .frame {
        border: 7px solid #ccc;
        background: #eee;
        padding: 15px 10px;
    }

    /*Small Tablet*/
    @media screen and (min-width: 620px) {
        .heading {
            font-size: var(--size-lg);
        }

        .hour {
            font-size: var(--size-lg);
        }

        .list {
            padding: 0 100px;
        }
    }

    /*Large Tablet and Laptop*/
    @media screen and (min-width: 960px) {
        .heading {
            margin-bottom: 20px;
        }

        .list {
            padding: 0 50px;
        }
    }

    /*Desktop*/
    @media screen and (min-width: 1200px) {
        .heading {
            margin-bottom: 40px;
        }
        
        .list {
            padding: 0 200px;
        }
    } 
</style>
