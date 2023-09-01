<script>
    import LineBreak from '$lib/components/linebreak.svelte';
</script>

<div>
    <h1>Cal-Nev-Ha District &nbsp;&#40;CNH&#41;&nbsp;</h1>

    <div>
        <div class="paintingcolor box text frame shadow">
            <p>The CNH District of Circle K is a group of nine divisions &nbsp;&#40;Citrus, Capital, Central Coast, Desert Oasis, Foothill, Golden Gate, Metro, Paradise, and Sunset&#41;&nbsp; spread out across the states of California, Nevada, and Hawaii.  Chartered on December 12, 1957, the district was founded with 31 clubs. Now, with 71 clubs and over 2,500 members spanning the three states, Cal-Nev-Ha serves as a shining beacon to its fellow districts.</p> 
            
            <img src="whoweare/otherlogos/District Emblem.png" class="district-logo" alt="district">
        </div>

<!--width-->
        <!-- <div class="logo-box">
            <div class="row-1 flex justify-center">
                <img src="District Emblem.png" class="logo" alt="district">            
            </div>
            <div class="row-2 flex">
                <img src="logo_citrus_color.png" class="logo" alt="citrus">
                <img src="logo_capital_color.png" class="logo" alt="capital">
                <img src="logo_central_color.png" class="logo" alt="central">
            </div>
            <div class="row-3 flex">
                <img src="logo_desert_color.png" class="logo" alt="desert">
                <img src="logo_foothill_color.png" class="logo" alt="foothill">
                <img src="logo_golden_color.png" class="logo" alt="golden">
            </div>
            <div class="row-4 flex">
                <img src="logo_metro_color.png" class="logo" alt="metro">
                <img src="logo_paradise_color.png" class="logo" alt="paradise">
                <img src="logo_sunset_color.png" class="logo" alt="sunset"> 
            </div>
        </div> -->
    </div>

    <LineBreak />
</div>

<style>
    h1 {
        color: white;
    }
    
    p {
        color: black;
    }

    h1 {
        font-size: var(--size-lg);
        text-align: center;
    }

    .district-logo {
        width: 150px;
        margin: auto;
        padding-top: 15px;
    }

    /* .logo {
        width: 150px;
        margin: auto;
    } */

    /* .logo-box {
        width: 300px;
        margin: auto;
    } */

    .frame {
        border: 10px ridge #cccccc;
        padding: 20px;
    }

    .shadow {
        box-shadow: 0px 10px 13px -7px #000000, 10px 12px 11px 4px rgba(0,0,0,0);
    }

    .box {
        margin: 16px 24px;        
    }

    .paintingcolor {
        background-color: #f0f0d8;
    }

    /*Small Tablet*/ 
    @media screen and (min-width: 620px) {
        .box {
            display: inline-flex;
            flex-direction: row-reverse;
            margin: 16px 50px 0 50px;            
        }

        .frame {
            padding: 25px;
        }

        p {
            font-size: var(--size-md);
        }

        .district-logo {
            padding: 0 25px 0 0;
        }
    }

    /*Large Tablet and Laptop*/
    @media screen and (min-width: 960px) {
        .box {
            margin: 16px 100px 0 100px;
        }

        .frame {
            padding: 35px;
        }

        img {
            padding: 0 35px 0 0;
        }
    }

    /*Desktop*/
    @media screen and (min-width: 1200px) {
        .box {
            margin: 20px 200px 0 200px;
        }
    } 
</style>