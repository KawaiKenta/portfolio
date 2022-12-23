<script>
  import Content from "./components/Content.svelte";
  import Header from "./components/Header.svelte";
  import Title from "./components/Title.svelte";

  const width = window.innerWidth;
</script>

{#if width > 768}
  <div class="header">
    <Header />
  </div>
{/if}
<section id="title">
  <Title />
</section>
<Content />

<style>
  .header {
    position: sticky;
    z-index: 1;
    top: 0;
  }
</style>
