<script>
  import Banner from "./components/Banner.svelte";
  import Detail from "./components/Detail.svelte";
  import Map from "./components/Map.svelte";
</script>

<!-- template -->
<main>
  <Banner />
  <Detail />
  <Map />
</main>

<style global lang="scss">
  @tailwind base;
  @tailwind components;
  @tailwind utilities;

  section {
    padding: 80px 0;

    &:nth-child(even) {
      background-color: var(--blue);
    }
  }
</style>
