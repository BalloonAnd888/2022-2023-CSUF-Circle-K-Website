<script>
    import LineBreak from '$lib/components/linebreak.svelte';
</script>

<div class="background text-white">
    <h1 class="text-white text-3xl text-center p-6">Appointed Board</h1>

    <div class="list animate__animated animate__fadeInLeft">
        <div class="first-row">
            <div class="flex justify-center p-8">
                <div class="shadow-lg bg-white max-w-sm">
                    <img src="board/alexis.jpg" class="mx-auto w-80" alt="Avatar"/>
                    <div class="p-6">
                        <div class="border-2 border-gray-800">
                            <h5 class="text-gray-900 text-xl font-medium mb-2 pt-2 text-center">Alexis Abucejo</h5>
                            <p class="text-gray-800 text-base mb-2 text-center">Fundraising Chair</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="flex justify-center p-8">
                <div class="shadow-lg bg-white max-w-sm">
                    <img src="board/brandon.jpg" class="mx-auto w-80 h-auto" alt="Avatar"/>
                    <div class="p-6">
                        <div class="border-2 border-gray-800">
                            <h5 class="text-gray-900 text-xl font-medium mb-2 pt-2 text-center">Brandon La</h5>
                            <p class="text-gray-800 text-base mb-2 text-center">Historian</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="flex justify-center p-8">
                <div class="shadow-lg bg-white max-w-sm">
                    <img src="board/ben.jpg" class="mx-auto w-80" alt="Avatar"/>
                    <div class="p-6">
                        <div class="border-2 border-gray-800">
                            <h5 class="text-gray-900 text-xl font-medium mb-2 pt-2 text-center">Benjamin Distor</h5>
                            <p class="text-gray-800 text-base mb-2 text-center">Public Relations Chair</p>
                        </div>
                    </div>
                </div>
            </div>            
        </div>

        <div class="second-row">
            <div class="flex justify-center p-8">
                <div class="shadow-lg bg-white max-w-sm">
                    <img src="board/kat.jpg" class="mx-auto w-80" alt="Avatar"/>
                    <div class="p-6">
                        <div class="border-2 border-gray-800">
                            <h5 class="text-gray-900 text-xl font-medium mb-2 pt-2 text-center">Kat Lu</h5>
                            <p class="text-gray-800 text-base mb-2 text-center">Publication Chair</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="flex justify-center p-8">
                <div class="shadow-lg bg-white max-w-sm">
                    <img src="board/andrew.jpg" class="mx-auto w-80" alt="Avatar"/>
                    <div class="p-6">
                        <div class="border-2 border-gray-800">
                            <h5 class="text-gray-900 text-xl font-medium mb-2 pt-2 text-center">Andrew Lau</h5>
                            <p class="text-gray-800 text-base mb-2 text-center">Technology Chair</p>
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