<script>
    import LineBreak from '$lib/components/linebreak.svelte';
</script>

<div class="background text-white">
    <h1 class="text-white text-3xl text-center p-6 animate__animated animate__fadeIn">Executive Board</h1>

    <div class="list animate__animated animate__fadeInLeft">
        <div class="first-row">
            <div class="flex justify-center p-8">
                <div class="shadow-lg bg-white max-w-sm">
                    <img src="board/megan.jpg" class="mx-auto w-80" alt="Avatar"/>
                    <div class="p-6">
                        <div class="border-2 border-gray-800">
                            <h5 class="text-gray-900 text-xl font-medium mb-2 pt-2 text-center">Megan Nguyen</h5>
                            <p class="text-gray-800 text-base mb-2 text-center">President</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="flex justify-center p-8">
                <div class="shadow-lg bg-white max-w-sm">
                    <img src="board/kristina.jpg" class="mx-auto w-80" alt="Avatar"/>
                    <div class="p-6">
                        <div class="border-2 border-gray-800">
                            <h5 class="text-gray-900 text-xl font-medium mb-2 pt-2 text-center">Kristina Matsumoto</h5>
                            <p class="text-gray-800 text-base mb-2 text-center">Vice President of Administration</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="flex justify-center p-8">
                <div class="shadow-lg bg-white max-w-sm">
                    <img src="board/james.jpg" class="mx-auto w-80" alt="Avatar"/>
                    <div class="p-6">
                        <div class="border-2 border-gray-800">
                            <h5 class="text-gray-900 text-xl font-medium mb-2 pt-2 text-center">James Balancio</h5>
                            <p class="text-gray-800 text-base mb-2 text-center">Vice President of Service</p>
                        </div>
                    </div>
                </div>
            </div>            
        </div>

        <div class="second-row">
            <div class="flex justify-center p-8">
                <div class="shadow-lg bg-white max-w-sm">
                    <img src="board/jungsuk.jpg" class="mx-auto w-80" alt="Avatar"/>
                    <div class="p-6">
                        <div class="border-2 border-gray-800">
                            <h5 class="text-gray-900 text-xl font-medium mb-2 pt-2 text-center">Jungsuk Ryow</h5>
                            <p class="text-gray-800 text-base mb-2 text-center">Secretary</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="flex justify-center p-8">
                <div class="shadow-lg bg-white max-w-sm">
                    <img src="board/elizabeth.jpg" class="mx-auto w-80" alt="Avatar"/>
                    <div class="p-6">
                        <div class="border-2 border-gray-800">
                            <h5 class="text-gray-900 text-xl font-medium mb-2 pt-2 text-center">Elizabeth Barajas</h5>
                            <p class="text-gray-800 text-base mb-2 text-center">Treasurer</p>
                        </div>
                    </div>
                </div>
            </div> 
        </div>
    </div>
</div>

<style>
    /*Small Tablet*/ 
    @media screen and (min-width: 620px) {
        .second-row {
            display: flex;
            justify-content: center;
        }
    }

    /*Large Tablet and Laptop*/
    @media screen and (min-width: 960px) {
        .first-row {
            display: flex;
            justify-content: center;
        }
    }

    /*Desktop*/
    @media screen and (min-width: 1200px) {
        
    } 
</style>