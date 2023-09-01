<script>
    import LineBreak from '$lib/components/linebreak.svelte';
</script>

<div class="block">
    <div class="heading-text size-md font-bold m-auto animate__animated animate__fadeIn animate__slower">
        <span class="text-center">Welcome to Circle K International at</span>
        <span class="text-center">California State University Fullerton!<span>        
    </div>

    <div class="px-4 m-auto animate__animated animate__fadeIn animate__delay-2s animate__slow">
        <img class="picture lg:hover:scale-110 transition duration-300 ease-in-out" src="home/CSUFFTC.jpg" alt="FTC2021">
    </div>  

    <LineBreak />
</div>

<style>
    .heading-text {
        color: white;
        padding: 30px 0;
    }

    span {
        display: block;
    }

    .picture {
        margin: auto;
        /* width: auto; */
        border: 10px solid #ccc;
    }

    /*Small Tablet*/
    @media screen and (min-width: 620px) {
        .heading-text {
            font-size: var(--size-lg);            
            padding: 30px 0;
        }

        .picture {
            border: 15px solid #ccc;
        }
    }

    /*Large Tablet and Laptop*/
    @media screen and (min-width: 960px) {
        .heading-text {
            padding: 40px 0;
        }

        .picture {
            height: 500px;
            border: 20px solid #ccc;
        }
    }

    /*Desktop*/
    @media screen and (min-width: 1200px) {
        .heading-text {
            font-size: var(--size-xxl);
            padding: 50px 0;
        }
    }
</style>