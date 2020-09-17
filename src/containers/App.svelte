<script>
  import Header from '../components/Header.svelte';
  import Main from '../components/Main.svelte';
  import Map from '../components/Map.svelte';
</script>

<style>
  :global(body) {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

</style>
<Header />
<Main>
  <Map />
</Main>
