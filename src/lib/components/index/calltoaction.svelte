<script>
    import LineBreak from '$lib/components/linebreak.svelte';
</script>
<div>
    <span class="size-md block text-white text-center px-5 m-auto animate__animated animate__fadeInLeftBig animate__slow">
        Love serving the community, building leadership skills, and fostering fellowship with their peers? Sounds like you? Awesome! Please feel free to explore our site and learn more about us!
    </span>

    <div class="list pt-16">
        <div class="p-4 animate__animated animate__fadeIn animate__slow">
            <a href="https://docs.google.com/spreadsheets/d/1mqJ_ZPBoUBsXMSQJTK0jkiz4-XNZWl4gYVfTLJveUfg/edit?usp=sharing" target="_blank" class="button rounded shadow-md hover:shadow-lg active:shadow-lg transition duration-500 ease-in-out">March Service Calendar</a>            
        </div>

        <div class="p-4 animate__animated animate__fadeIn animate__slow">
            <a href="https://csufckizine.carrd.co/" target="_blank" class="button rounded shadow-md hover:shadow-lg active:shadow-lg transition duration-500 ease-in-out">CSUF Circle K Zine</a>            
        </div>

        <div class="p-4 animate__animated animate__fadeIn animate__slow">
            <a href="https://forms.gle/A7cLUcsbbkV3tZx58" target="_blank" class="button rounded shadow-md hover:shadow-lg active:shadow-lg transition duration-500 ease-in-out">Membership Form</a>            
        </div>

        <!-- <div class="p-4 animate__animated animate__fadeIn animate__slow">
            <a href="https://tinyurl.com/2324ABoardApp" target="_blank" class="button rounded shadow-md hover:shadow-lg active:shadow-lg transition duration-500 ease-in-out">ABoard Apps</a>            
        </div> -->

        <div class="p-4 animate__animated animate__fadeIn animate__slow">
            <a href="/socialmedia" class="button rounded shadow-md  hover:shadow-lg active:shadow-lg transition duration-500 ease-in-out">Social Media</a>
        </div>

        <div class="p-4 animate__animated animate__fadeIn animate__slow">
            <a href="/calendar" class="button rounded shadow-md  hover:shadow-lg active:shadow-lg transition duration-500 ease-in-out">Calendar</a>
        </div>
    </div>

    <LineBreak />
</div>

<style>
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
        background-color: #E3EDF2;
        color: black;
    }

    /*Small Tablet*/
    @media screen and (min-width: 620px) {
        span {
            font-size: var(--size-lg);
            padding: 0 50px;
        }
    }

    /*Large Tablet and Laptop*/
    @media screen and (min-width: 960px) {
        span {
            padding: 0 80px;
        }

        .button {
            width: 250px;
        }
    }

    /*Desktop*/
    @media screen and (min-width: 1200px) {
        span {
            padding: 0 200px;
        }
    } 
</style>