<script>
    import "../input.css";
    import NavBar from '$lib/components/navbar.svelte';
    import Footer from '$lib/components/footer.svelte';
</script>

<NavBar /> 
<main><slot /></main>
<Footer />

<svelte:head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
</svelte:head>

<style>
  main {
    min-height: 100vh;
    display: flex;
    flex-direction: column;

    
    /* min-height: calc(100vh - 370px); main - (header_height+margin+footer_height+margin) */
    
  }
</style>

