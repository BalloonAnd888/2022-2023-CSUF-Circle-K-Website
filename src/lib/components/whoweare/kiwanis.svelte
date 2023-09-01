<div>
    <h1>Kiwanis International</h1>

    <div class="paintingcolor box frame shadow">
        <div>
            <p>A true global service organization dedicated to improving the lives of children from different communities and geographic areas, Kiwanis International is also the umbrella that all its other branches stem from. K-Kids, Builder's Club, Key Club, KIWINS, Circle K, and Aktion Club are all part of the Kiwanis Family.</p>

            <br>

            <p class="text-center">The Kiwanis Club of Fullerton sponsors Circle K International at Cal State Fullerton</p>

            <img src="whoweare/otherlogos/kiwanis_color.png" alt="kiwanis" class="logo"> 
        </div>
    </div>
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

    .logo {
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
        margin: 16px 24px 20px 24px;        
    }

    .paintingcolor {
        background-color: #f0f0d8;
    }

    /*Small Tablet*/ 
    @media screen and (min-width: 620px) {
        .box {
            display: inline-flex;
            flex-direction: row-reverse;
            margin: 16px 50px 40px 50px;
        }

        .frame {
            padding: 25px;
        }

        p {
            font-size: var(--size-md);
        }

        .logo {
            padding: 25px 0 0 0;
        }
    }

    /*Large Tablet and Laptop*/
    @media screen and (min-width: 960px) {
        .box {
            margin: 16px 100px 70px 100px;
        }

        .frame {
            padding: 35px;
        }

        .logo {
            padding: 35px 0 0 0;
        }
    }

    /*Desktop*/
    @media screen and (min-width: 1200px) {
        .box {
            margin: 20px 200px 100px 200px;
        }
    } 
</style>