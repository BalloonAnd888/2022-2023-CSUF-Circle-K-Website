<script>
    import LineBreak from '$lib/components/linebreak.svelte';
</script>

<div class="text-white">
    <h1 class="size-xl text-center animate__animated animate__fadeIn animate__slow">Fellowship</h1>        

    <p class="description size-md px-5 m-auto animate__animated animate__fadeIn animate__slow">Fellowship, our last tenet, consists of social side of our club. Whether you want to attend an after-meeting social to get to know other members, or go to a member-exclusive retreat up in the mountains during the winter, this tenet is meant to help our members develop lasting and meaningful relationships, and help unite the club. You can also get a chance to meet other Circle K members from other schools all around California, Nevada, and Hawaii! Fellowship is implemented virtually everywhere here in our club, even in events that may at first seem strictly tied to service & leadership. But don't worry, we have plenty of fellowship events consistently planned throughout the whole year for you to bond and get to know your fellow members. There are also amazing programs implemented within our club to truly enhance your Circle K experience. For instance, potential members have the opportunity to become a Mentee/Little in our Mentor/Mentee program a.k.a. our Big/Little program. Additionally, members can also be placed in our Family System where they can get to know other members in a smaller group setting and compete against other Families throughout the year. Lastly, one of the biggest fellowship events potential members can attend are our seasonal retreats, with the most popular being our winter retreat called Snowcial! Whether you're starting out in college for the first time, or trying to find your second home, we understand it can be rather tough & daunting, but here at CSUF Circle K, we hope that we can help you pick your perfect destination! </p>

    <LineBreak />
</div>

<style>
    h1 {
        padding: 30px 0;
    }

    /*Small Tablet*/ 
    @media screen and (min-width: 620px) {
        .description {
            padding: 0 50px;
        }
    }

    /*Large Tablet and Laptop*/
    @media screen and (min-width: 960px) {
        .description {
            padding: 0 80px;
        }
    }

    /*Desktop*/
    @media screen and (min-width: 1200px) {
        .description {
            padding: 0 200px;
        }
    } 
</style>
