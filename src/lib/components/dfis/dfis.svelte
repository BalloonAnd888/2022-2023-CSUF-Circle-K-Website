<script>
    import LineBreak from '$lib/components/linebreak.svelte';
</script>

<div class="text-white">
    <h1 class="size-xl text-center animate__animated animate__fadeIn animate__slow">District Fundraising Initiatives</h1>        

    <div class="text-center px-5 mb-5">
        <div class="animate__animated animate__fadeInLeft">
            <img src="board/alexis.jpg" class="frame shadow w-[500px] mb-4 mx-auto lg:hover:scale-110 transition duration-300 ease-in-out" alt="alexis">
        </div>
        <div class="animate__animated animate__fadeIn animate__slower">
            <h2 class="size-md font-medium">Alexis Abucejo</h2>
            <h2 class="size-md font-medium">Fundraising Chair</h2>
        </div>
    </div>

    <p class="description size-md px-5 pb-5 m-auto">Within our club, we donate money to our three District Fundraising Initiatives; the Pediatric Trauma Program, Kiwanis Family House and UNICEF. The Pediatric Trauma Program &nbsp;&#40;PTP&#41;&nbsp; aims to develop local projects which will help to reduce the incidence of children that are killed by trauma within the three state district, Cal-Nev-Ha. The funds raised will contribute towards the funding of these local projects as well as provide safety items for children. The Kiwanis Family House aims to build a supportive community around families who are impacted by medical emergencies within UC Davis Children's Hospital in Sacramento. Funds raised within this DFI will help to provide additional resources to families as well as improve the stay for the impacted families. UNICEF is a worldwide organization that helps to provide vaccines, support children's health and nutrition, provide sanitation and safe water and provides quality education to disadvantaged children. Funds raised will help to provide the resources needed to accomplish the organization's goals of providing better living for underprivileged children.</p>

    <div class="box container m-auto grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 lg:gap-8 animate__animated animate__fadeInLeft">
        <div class="paintingcolor frame p-4 mb-5 shadow col-span-1 flex flex-col lg:hover:scale-110 transition duration-300 ease-in-out">
            <h5 class="text-black size-md text-center font-medium pb-2">Pediatric Trauma Program &nbsp;&#40;PTP&#41;</h5>
            <p class="text-gray-900 size-md text-center mt-auto  mb-4">
                Develops local projects which will reduce the number of children who are killed or injured by trauma
            </p>                    
            <div class="mt-auto mb-2 flex flex-wrap justify-center">
                <a href="https://www.cnhfoundation.org/what-we-do/pediatric-trauma-program/" target="_blank" class="button px-6 pt-2.5 pb-2 text-white font-medium leading-normal rounded shadow-md hover:shadow-lg transition duration-500 ease-in-out flex align-center">Learn More</a>
            </div>
        </div>
        
        <div class="paintingcolor frame p-4 mb-5 shadow col-span-1 flex flex-col lg:hover:scale-110 transition duration-300 ease-in-out">
            <h5 class="text-black size-md text-center font-medium pb-2">Kiwanis Family House &nbsp;&#40;KFH&#41;</h5>
            <p class="text-gray-900 size-md text-center mt-auto mb-4">
                Provides housing and support to families of seriously ill or injured children as well as adults being treated in the UC Davis Medical Center located in Sacramento, CA
            </p>                    
            <div class="mt-auto mb-2 flex flex-wrap justify-center">
                <a href="https://kiwanisfamilyhouse.org/who-we-are/mission-history/" target="_blank" class="button px-6 pt-2.5 pb-2 text-white font-medium leading-normal rounded shadow-md hover:shadow-lg transition duration-500 ease-in-out flex align-center">Learn More</a>
            </div>
        </div>

        <div class="paintingcolor frame p-4 mb-5 shadow col-span-1 flex flex-col lg:hover:scale-110 transition duration-300 ease-in-out">
            <h5 class="text-black size-md text-center font-medium pb-2">UNICEF</h5>
            <p class="text-gray-900 size-md text-center mt-auto mb-4">
                World's largest provider of vaccines which supports child health and nutrition, safe water and sanitation, quality education and skill building, HIV prevention and treatment for mothers and babies, and the protection of children and adolescents from violence and exploitation 
            </p>                    
            <div class="mt-auto mb-2 flex flex-wrap justify-center">
                <a href="https://www.unicef.org/what-we-do" target="_blank" class="button px-6 pt-2.5 pb-2 text-white font-medium leading-normal rounded shadow-md hover:shadow-lg transition duration-500 ease-in-out flex align-center">Learn More</a>

            </div>
        </div>

        <!-- <div class="frame p-4 mb-5 shadow bg-white col-span-1 flex flex-col lg:hover:scale-110 transition duration-300 ease-in-out">
            <h5 class="text-black size-md text-center font-medium pb-2">Born This Way Foundation &nbsp;&#40;Governor's Project&#41</h5>
            <p class="text-gray-900 size-md text-center mt-auto mb-4">
                An organization that aims to support and uplift the voices of students around the world, specifically regarding the conversation about Mental Health 
            </p>                    
            <div class="mt-auto mb-2 flex flex-wrap justify-center">
                <a href="https://bornthisway.foundation/our-mission/" class="block px-6 py-2.5 bg-gray-200 text-black font-medium text-xl leading-tight  rounded shadow-md hover:bg-gray-400 hover:shadow-lg focus:bg-white focus:shadow-lg focus:outline-none focus:ring-0 transition duration-150 ease-in-out" target="_blank">Learn More</a>
            </div>
        </div> -->
    </div>

    <LineBreak />
</div>

<style>
    h1 {
        padding: 30px 0;
    }

    .frame {
        border: 10px ridge #cccccc;
    }

    .shadow {
        box-shadow: 0px 10px 13px -7px #000000, 10px 12px 11px 4px rgba(0,0,0,0);
    }

    .button {
        font-size: var(--size-sm);
        background-color: #babcc9;
    }

    .button:hover {
        background-color: #E3EDF2;
        color: black;
    }

    .paintingcolor {
        background-color: #f0f0d8;
    }

    .box {
        padding: 20px 24px 0px 24px;
    }

    /*Small Tablet*/ 
    @media screen and (min-width: 620px) {
        .box {
            padding: 30px 34px 0px 34px;
        }

        .description {
            padding: 0 50px;
        }
    }

    /*Large Tablet and Laptop*/
    @media screen and (min-width: 960px) {
        .box {
            padding-right: 80px;
            padding-left: 80px;
        }

        .description {
            padding: 0 80px;
        }
    }

    /*Desktop*/
    @media screen and (min-width: 1200px) {
        .box {
            padding-right: 125px;
            padding-left: 125px;
        }

        .description {
            padding: 0 200px;
        }
    } 
</style>