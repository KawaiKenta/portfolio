<script>
  import Progress from "./Progress.svelte";
</script>

<div class="container">
  <h3>Native</h3>
  <div>
    <ul>
      <li><Progress name={"Flutter"} percentage={60} /></li>
    </ul>
  </div>
</div>

<style>
  ul {
    display: flex;
    align-items: center;
    justify-content: center;
    padding-left: 0;
  }
  li {
    list-style: none;
    width: 100%;
  }

  h3 {
    font-size: 20px;
    margin-bottom: 8px;
  }
  .container {
    padding: 0.8em;
  }
</style>
