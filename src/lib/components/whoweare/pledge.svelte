<script>
    import LineBreak from '$lib/components/linebreak.svelte';
</script>

<div>
    <h2 class="size-md text-center font-bold pb-4 m-auto animate__animated animate__fadeInLeft">Circle K Pledge</h2>

    <div class="animate__animated animate__fadeInLeft animate__delay-1s">
        <p class="frame paintingcolor shadow text size-sm text-center font-bold py-4 px-6 m-auto">"I pledge to uphold the objects of Circle K International, to foster compassion and goodwill towards others through service and leadership. To develop my abilities and the abilities of all people, and to dedicate myself to the realization of humanity's potential!"</p>
    </div>

    <LineBreak />
</div>

<style>
    h2 {
        color: white;
    }

    .text {
        color: black;
    }

    .frame {
        border: 10px ridge #cccccc;
        margin: 0 24px;
    }

    .shadow {
        box-shadow: 0px 10px 13px -7px #000000, 10px 12px 11px 4px rgba(0,0,0,0);
    }

    .paintingcolor {
        background-color: #f0f0d8;
    }

    /*Small Tablet*/ 
    @media screen and (min-width: 620px) {        
        h2 {
            font-size: var(--size-lg);
        }

        .text {
            font-size: var(--size-md);
        }

        .frame {
            margin: 0 50px;
        }
    }

    /*Large Tablet and Laptop*/
    @media screen and (min-width: 960px) {
        h2 {
            padding-bottom: 30px;
        }     

        .text {
            padding: 32px 40px;
        }

        .frame {
            margin: 0 100px;
        }
    }

    /*Desktop*/
    @media screen and (min-width: 1200px) {
        .text {
            padding: 52px 60px;
        }

        .frame {
            margin: 0 200px;
        }
    } 
</style>