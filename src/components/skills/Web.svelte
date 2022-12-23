<script>
  import Progress from "./Progress.svelte";
</script>

<div class="container">
  <h3>WEB</h3>
  <div>
    <h4>Frotend</h4>
    <ul>
      <li><Progress name={"Vue3"} percentage={70} /></li>
      <li><Progress name={"Svelte"} percentage={60} /></li>
    </ul>
  </div>

  <div>
    <h4>Backend</h4>
    <ul>
      <li><Progress name={"Gin"} percentage={90} /></li>
      <li><Progress name={"Codeigniter4"} percentage={60} /></li>
    </ul>
  </div>
  <div>
    <h4>Database</h4>
    <ul>
      <li><Progress name={"MySQL"} percentage={70} /></li>
      <li><Progress name={"SQlite3"} percentage={70} /></li>
    </ul>
  </div>
</div>

<style>
  ul {
    display: flex;
    align-items: center;
    padding-left: 0px;
  }
  li {
    list-style: none;
    width: 100%;
  }
  h3 {
    font-size: 20px;
    margin-bottom: 8px;
  }
  h4 {
    margin-bottom: 4px;
  }
  .container {
    padding: 0.8em;
    margin-bottom: 4px;
  }
</style>
