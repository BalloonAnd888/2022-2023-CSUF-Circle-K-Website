<div class="week-month w-auto text-center">
    <!-- Member of the Week (Not in use) -->
    <!-- <div class="heading pb-3" data-aos="fade" data-aos-once="true" data-aos-anchor-placement="top-bottom" data-aos-duration="2000">
        <h1 class="heading px-8 pb-4 font-bold underline">Member of the Week &#40;Week #&#41;</h1>
        <div class="px-4 lg:hover:scale-110 transition duration-300 ease-in-out">
            <img class="frame m-auto" src="testassets/whiteboxtemp.png" alt="temp">
        </div>
    </div> -->
    
    <!-- Member of the Month -->
    <div class="heading" data-aos="fade" data-aos-once="true" data-aos-anchor-placement="top-bottom" data-aos-duration="2000">
        <h1 class="heading px-8 pb-4 font-bold underline">Member of the Month &nbsp;&#40;February&#41;</h1>
        <div class="px-5">
            <img class="frame m-auto lg:hover:scale-110 transition duration-300 ease-in-out" src="mom/brian_zee.jpg" alt="temp">
        </div>
        <p class="pt-2">Brian Zee</p>
    </div>   
</div>

<style>
    .heading {
        color: white;
        text-align: center;
        font-size: var(--size-md);
    }

    .week-month {
        margin-bottom: 20px;
    }

    .frame {
        margin: auto;
        width: auto;
        border: 10px solid #ccc;
        width: 300px;
    }

    /*Small Tablet*/
    @media screen and (min-width: 620px) {
        .heading {
            font-size: var(--size-lg);
        }

        .week-month {
            margin-bottom: 40px;
        }

        .frame {
            border: 15px solid #ccc;
        }
    }

    /*Large Tablet and Laptop*/
    @media screen and (min-width: 960px) {
        .week-month {
            display: flex;
            justify-content: space-around;
            margin-bottom: 70px;            
        }

        h1 {
            padding: 20px;
        }

        .frame {
            border: 20px solid #ccc;
        }
    }

    /*Desktop*/
    @media screen and (min-width: 1200px) {
        .week-month {
            margin-bottom: 100px;
        }
    } 
</style>