<script>
    import LineBreak from '$lib/components/linebreak.svelte';
</script>

<div>
    <h1>Citrus Division</h1>

    <div class="paintingcolor box frame shadow">
        <p>CKI at CSUF is a part of Citrus Division within CNH Circle K. The Citrus Division is a group of five Circle K clubs located primarily in Orange County. These clubs collaborate with one another through events such as monthly Divisional Council Meetings &nbsp;&#40;DCMs&#41;&nbsp; and monthly Divisional Service Projects &nbsp;&#40;DSPs&#41;.  We're always staying fresh in Citrus Division!</p>

        <img src="whoweare/divisionlogo/logo_citrus_color.png" alt="citruslogo">
    </div>

    <div class="paintingcolor clubbox frame shadow">
        <h2 class="pb-4">Clubs in Citrus Division</h2>
        <div class="text-center">
            <p class="pb-2">CSUF Thursdays at 6PM at TSU Alvarado</p>
            <p class="pb-2">IVC Bi-Weekly Wednesdays at 3:30 PM</p>
            <p class="pb-2"><a href="https://occcirclek.org/">OCC</a> Thursdays at 4:15 PM at Student Union 213</p>
            <p class="pb-2">Saddleback N/A</p>
            <p><a href="https://ucicirclek.com/">UCI</a> Mondays at 7 PM at HIB 100</p>
        </div>
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

    h1, h2 {
        font-size: var(--size-lg);
        text-align: center;
    }

    img {
        width: 150px;
        margin: auto;
        padding-top: 15px;
    }

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

    .clubbox {
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

        .clubbox {
            margin: 16px 50px 0 50px;
        }

        .frame {
            padding: 25px;
        }

        p {
            font-size: var(--size-md);
        }

        img {
            padding: 0 25px 0 0;
        }
    }

    /*Large Tablet and Laptop*/
    @media screen and (min-width: 960px) {
        .box {
            margin: 16px 100px 0 100px;
        }

        .clubbox {
            margin: 16px 100px 0 100px;
        }

        .frame {
            padding: 35px;
        }

        img {
            padding: 0 35px 0 0;
        }

        a:hover {
            text-decoration: underline;
            font-weight: bold;
        }
    }

    /*Desktop*/
    @media screen and (min-width: 1200px) {
        .box {
            margin: 20px 200px 0 200px;
        }

        .clubbox {
            margin: 20px 200px 0 200px;
        }

        a:hover {
            text-decoration: underline;
            font-weight: bold;
        }
    } 
</style>