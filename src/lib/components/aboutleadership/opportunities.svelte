<script>
    import LineBreak from '$lib/components/linebreak.svelte';
</script>

<div>
    <h1 class="text-white size-lg text-center pb-10">Leadership Opportunities</h1>

    <div class="box container m-auto grid grid-cols-1 lg:grid-cols-3 lg:gap-8 animate__animated animate__fadeInLeft">
        <div class="paintingcolor frame p-4 mb-5 shadow bg-white col-span-1 flex flex-col lg:hover:scale-110 transition duration-300 ease-in-out">
            <h5 class="text-black size-md border-b text-center font-medium pb-4">Board</h5>
            <div class="pt-4">
                <p class="text-gray-900 size-md font-medium text-center mb-4">Want to take your passion for CKI to the next level?</p>
                <p class="text-gray-900 size-md text-center mb-4">Board Officers are one of the bigger roles within Circle K and require much drive and responsibility. Not only do board officers host events and create resources, but they also ensure that everything within the club runs smoothly and effectively. Members interested in becoming a board officer have the opportunity to run for an Executive Board position or apply for an Appointed Board position. In addition, members can also run for District and International board positions. Meet CSUF Circle K's 2022-2023 Board <a href="/boardofficers"><b>here</b></a>. 
                </p>                    
            </div>
        </div>

        <div class="paintingcolor frame p-4 mb-5 shadow bg-white col-span-1 flex flex-col lg:hover:scale-110 transition duration-300 ease-in-out">
            <h5 class="text-black size-md border-b text-center font-medium pb-4">Committees</h5>
            <div class="pt-4">
                <p class="text-gray-900 size-md font-medium text-center mb-4">Interested in the behind the scenes of CKI?</p>
                <p class="text-gray-900 size-md text-center mb-4">This year, our club offers six different committees that all members are welcome to be a part of! These include FTC Skit,  Fundraising, Media, Service, Spirit & Technology!  Beyond the club level, members are encouraged to join District and International committees as well. 
                </p>                    
            </div>
        </div>

        <div class="paintingcolor frame p-4 mb-5 shadow bg-white col-span-1 flex flex-col lg:hover:scale-110 transition duration-300 ease-in-out">
            <h5 class="text-black size-md border-b text-center font-medium pb-4">Conventions</h5>
            <div class="pt-4">
                <p class="text-gray-900 size-md font-medium text-center mb-4">Want to meet new people and learn new skills?</p>
                <p class="text-gray-900 size-md text-center my-auto mb-4">Conventions are large-scale events where members have the opportunity to attend workshops, learn more about Circle K, and make new connections & friends! Every year, there are three conventions hosted by CNH Circle K: Fall Training Conference, District Convention, Spring Training Conference. On the international level, there is CKIx, which is hosted every summer where members can interact with clubs all over the world, gain professional skills, and more!
                </p>                    
            </div>
        </div>

        <div class="paintingcolor frame p-4 mb-5 shadow bg-white col-span-1 flex flex-col lg:hover:scale-110 transition duration-300 ease-in-out">
            <h5 class="text-black size-md border-b text-center font-medium pb-4">Event Chair</h5>
            <div class="pt-4">
                <p class="text-gray-900 size-md font-medium text-center mb-4">Interested in event planning and coordinating?</p>
                <p class="text-gray-900 size-md text-center my-auto mb-4">An event chair is in charge of overlooking an event and making sure that it runs smoothly. By chairing an event, individuals can improve their leadership and communication skills by directing and informing members. If you are interested in chairing a service event, please contact our Vice President of Service, James Balancio!
                </p>                    
            </div>
        </div>

        <div class="paintingcolor frame p-4 mb-5 shadow bg-white col-span-1 flex flex-col lg:hover:scale-110 transition duration-300 ease-in-out">
            <h5 class="text-black size-md border-b text-center font-medium pb-4">Family Head</h5>
            <div class="pt-4">
                <p class="text-gray-900 size-md font-medium text-center mb-4">Love fellowship and connecting with club members?</p>
                <p class="text-gray-900 size-md text-center my-auto mb-4">Family Heads are an integral part of the Family System, which allows members to bond with each other in smaller groups. Family Heads lead their families, host family activities, and encourage members to actively participate in the club. This year, we have 3 Family Heads and Families! learn more about our Family Head and their Families <a href="/familysystem"><b>here</b></a>. 
                </p>                    
            </div>
        </div>

        <div class="paintingcolor frame p-4 mb-5 shadow bg-white col-span-1 flex flex-col lg:hover:scale-110 transition duration-300 ease-in-out">
            <h5 class="text-black size-md border-b text-center font-medium pb-4">Workshop Host</h5>
            <div class="pt-4">
                <p class="text-gray-900 size-md font-medium text-center mb-4">Want to share something with the club?</p>
                <p class="text-gray-900 size-md text-center my-auto mb-4">Members are encouraged to host workshops about any appropriate topic they are passionate about to educate others and share their interests! By hosting workshops, individuals can develop their public speaking and professional skills. Workshops can be hosted at club meetings, as well as during divisional, district, and international events. If you are interested in hosting a workshop for our club, please fill out this form!
                </p>                    
            </div>
        </div>
    </div>

    <LineBreak />
</div>

<style>
    .box {
        padding: 0 20px;
    }

    .frame {
        border: 10px ridge #cccccc;
    }
    
    .shadow {
        box-shadow: 0px 10px 13px -7px #000000, 10px 12px 11px 4px rgba(0,0,0,0);
    }

    .paintingcolor {
        background-color: #f0f0d8;
    }

    /*Small Tablet*/ 
    @media screen and (min-width: 620px) {
        .box {
            padding: 0 30px;
        }
    }

    /*Large Tablet and Laptop*/
    @media screen and (min-width: 960px) {
        h1 {
            font-size: var(--size-lg);
        }

        .box {
            padding: 0 80px;
        }
    }

    /*Desktop*/
    @media screen and (min-width: 1200px) {
        .box {
            padding: 0 130px;
        }
    } 
</style>
