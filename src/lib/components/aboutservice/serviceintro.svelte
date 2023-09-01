<script>
    import LineBreak from '$lib/components/linebreak.svelte';
</script>

<div class="text-white">
    <h1 class="size-xl text-center animate__animated animate__fadeIn animate__slow">Service</h1>        

    <div class="text-center px-5 mb-5">
        <div class="animate__animated animate__fadeInLeft">
            <img src="board/james.jpg" class="frame shadow w-[500px] mb-4 mx-auto lg:hover:scale-110 transition duration-300 ease-in-out" alt="james">            
        </div>
        <div class="animate__animated animate__fadeIn animate__slower">
            <h2 class="size-md font-medium">James Balancio</h2>
            <h2 class="size-md font-medium">Vice President of Service</h2>
        </div>
    </div>

    <p class="description size-md px-5 m-auto">Service is our 1st tenet, and is what CKI is built on and around, driven by our passion to make this world a little better each time. In working towards that goal, we at CSUF Circle K offer our members a wide variety of service projects that provide everyone an opportunity to give back to their campus & communities. Whether you're building a whole playground for a low-income community, to helping distribute food to those who've been hit hard by COVID-19, to maintaining an endangered ecosystem, you'll be able to recognize the impact and meaning behind your efforts. Regardless of your background, the satisfaction of helping others is something we can all share here at CSUF Circle K.</p>

    <LineBreak />
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
        box-shadow: 0px 10px 13px -7px #000000, 10px 12px 11px 4px rgba(0,0,0,0);
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
    }

    /*Desktop*/
    @media screen and (min-width: 1200px) {
        .description {
            padding: 0 200px;
        }
    } 
</style>
