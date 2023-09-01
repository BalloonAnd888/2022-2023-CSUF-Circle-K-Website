<script>
    import LineBreak from '$lib/components/linebreak.svelte';
</script>

<div class="text-white">
    <h1 class="size-xl text-center animate__animated animate__fadeIn animate__slow">Leadership</h1>        

    <div class="text-center px-5 mb-5">
        <div class="animate__animated animate__fadeInLeft">
            <img src="board/kristina.jpg" class="frame shadow w-[500px] mb-4 mx-auto lg:hover:scale-110 transition duration-300 ease-in-out" alt="kristina">            
        </div>
        <div class="animate__animated animate__fadeIn animate__slower">
            <h2 class="size-md font-medium">Kristina Matsumoto</h2>
            <h2 class="size-md font-medium">Vice President of Administration</h2>
        </div>
    </div>

    <p class="description size-md px-5 m-auto">Leadership, our 2nd tenet, is centered around personal growth of the individual through learning and honing a new set of skills and being able to apply them to our club, school and community. And this isn't simply limited to those who have a title, such as Board; this quality is shared amongst all our members. It might seem impossible to have a club full of leaders, but this amazing home of ours gives all the ample opportunities to showcase our skills &amp; talents throughout the years. Whether acting as chair for a club event or participating in one of our club committees, there is always a chance you can take to improve yourself as a leader and as an individual here at CSUF Circle K!</p>

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
