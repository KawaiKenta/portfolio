<script>
  import Embedded from "./skills/Embedded.svelte";
  import Language from "./skills/Language.svelte";
  import Native from "./skills/Native.svelte";
  import Other from "./skills/Other.svelte";
  import Web from "./skills/Web.svelte";
  import Goapi from "./works/Goapi.svelte";
  import Portfolio from "./works/Portfolio.svelte";
</script>

<div class="background">
  <div class="container">
    <h2 id="projects">PROJECTS</h2>
    <Goapi />
    <Portfolio />
    <hr />
    <h2 id="skills">SKILLS</h2>
    <Language />
    <Web />
    <Native />
    <Embedded />
    <Other />
  </div>
</div>

<style>
  .background {
    background-color: rgba(0, 0, 0, 0.82);
    color: whitesmoke;
    padding: 20px 5%;
  }
  hr {
    border: 0.8px solid #6b6b6b;
    margin-top: 10px;
    margin-bottom: 40px;
  }
  h2 {
    font-size: 24px;
  }
</style>
