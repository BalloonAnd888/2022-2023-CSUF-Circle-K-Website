<script>
    import LineBreak from '$lib/components/linebreak.svelte';
</script>

<div>
    <h1 class="size-md text-center font-bold underline pb-4 animate__animated animate__fadeInLeft">What is Circle K International?</h1>
    
    <div class="animate__animated animate__fadeInLeft animate__delay-1s">
        <p class="frame paintingcolor shadow text size-sm text-center py-4 px-6 m-auto">Originally founded in 1936 as a fraternity at Washington State University, Circle K International original vision was to assist young men who needed financial aid attend college. Fast forward to 1947, and CKI was officially recognized as a service oriented organization, with the first club under this new vision being chartered at Carthage College in Carthage, Illinois. Today, CKI has over 13,000 members spread across 550 campuses worldwide, all centered around the goal of promoting & fostering its three tenets: service, leadership, and fellowship!<p>        
    </div>

    <LineBreak />
</div>

<style>
    h1 {
        color: white;
        padding: 30px 0;
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
        h1 {
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
        h1 {
            font-size: var(--size-xl);
            /* padding-bottom: 40px; */
            padding: 40px 0;
        }     

        .text {
            font-size: var(--size-lg);
            padding: 32px 40px;
        }

        .frame {
            margin: 0 100px;
        }
    }

    /*Desktop*/
    @media screen and (min-width: 1200px) {
        h1 {
            padding: 60px;
        }

        .text {
            padding: 52px 60px;
        }

        .frame {
            margin: 0 200px;
        }
    } 
</style>