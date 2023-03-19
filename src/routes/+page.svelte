<script>
  import PageOwner from "$lib/MainPage/PageOwner.svelte";
  import PageStats from "$lib/MainPage/PageStats.svelte";
  import PageMoto from "$lib/MainPage/PageMoto.svelte";
  import PageFeatures from "$lib/MainPage/PageFeatures.svelte";
  import PageHero from "$lib/MainPage/PageHero.svelte";
</script>

<svelte:head>
  <title>Option Analysis</title>
  <meta name="description" content="Analysis & Learn Option Trading" />
  <meta
    name="og:image"
    content="https://cdn-icons-png.flaticon.com/512/7314/7314483.png"
  />
</svelte:head>
<PageHero />
<PageMoto />
<PageFeatures />
<!-- <PageStats /> -->
<PageOwner />

<style lang="postcss">
</style>
