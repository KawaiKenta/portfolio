<script>
  import Content from "./components/Content.svelte";
  import Header from "./components/Header.svelte";
  import Title from "./components/Title.svelte";

  const width = window.innerWidth;
</script>

<div class="header">
  <Header />
</div>
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
