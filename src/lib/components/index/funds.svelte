<script>
    import LineBreak from '$lib/components/linebreak.svelte';
</script>

<div>
    <h1 class="heading px-4 pb-4 font-bold underline" data-aos="fade" data-aos-once="true" data-aos-anchor-placement="top-bottom" data-aos-duration="2100">
        Total Funds Raised &nbsp;&#40;As of February&#41;
    </h1>

    <div class="list container m-auto px-10 grid grid-cols-1 lg:grid-cols-2 lg:gap-8 animate__animated animate__fadeInLeft">
        <div class="frame fund p-4 mb-5 shadow bg-white col-span-1 flex flex-col lg:hover:scale-110 transition duration-300 ease-in-out">
            <h5 class="text-black text-center font-medium pb-2">Pediatric Trauma Program &nbsp;&#40;PTP&#41;</h5>
            <div class="my-auto">
                <p class="text-gray-900 size-md text-center">
                    $372.62
                </p>                    
            </div>
        </div>

        <div class="frame fund p-4 mb-5 shadow bg-white col-span-1 flex flex-col lg:hover:scale-110 transition duration-300 ease-in-out">
            <h5 class="text-black text-center font-medium pb-2">Kiwanis Family House &nbsp;&#40;KFH&#41;</h5>
            <div class="my-auto">
                <p class="text-gray-900 size-md text-center">
                    $570.28
                </p>                    
            </div>
        </div>

        <div class="frame fund p-4 mb-5 shadow bg-white col-span-1 flex flex-col lg:hover:scale-110 transition duration-300 ease-in-out">
            <h5 class="text-black text-center font-medium pb-2">UNICEF</h5>
            <div class="my-auto">
                <p class="text-gray-900 size-md text-center">
                    $495.63
                </p>                    
            </div>
        </div>

        <div class="frame fund p-4 mb-5 shadow bg-white col-span-1 flex flex-col lg:hover:scale-110 transition duration-300 ease-in-out">
            <h5 class="text-black text-center font-medium pb-2">Other Charities</h5>
            <div class="my-auto">
                <p class="text-gray-900 size-md text-center">
                    $168.80
                </p>                    
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

    .fund {
        font-size: var(--size-md);
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
