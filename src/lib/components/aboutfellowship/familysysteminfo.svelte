<script>
    import LineBreak from '$lib/components/linebreak.svelte';
</script>

<div>
    <h1 class="text-white size-lg text-center">Family System</h1>

    <p class="description text-white size-md px-5 py-5 m-auto text-center">Our family system is one the ways our members can bond with each other on a smaller, more defined scale.</p>

    <div class="p-4">
        <a href="/familysystem" class="button rounded shadow-md  hover:shadow-lg active:shadow-lg transition duration-500 ease-in-out">
            Learn More
        </a>            
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
        .description {
            padding: 20px 50px;
        }
    }

    /*Large Tablet and Laptop*/
    @media screen and (min-width: 960px) {
        .description {
            padding: 20px 80px;
        }
    }

    /*Desktop*/
    @media screen and (min-width: 1200px) {
        .description {
            padding: 20px 200px;
        }
    } 
</style>