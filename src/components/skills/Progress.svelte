<script>
  export let name;
  export let percentage;
</script>

<div class="skillbox">
  <div class="html">
    <h5>{name}</h5>
    <span class="percentage">{percentage}%</span>
    <div class="cover">
      <div class="progressbar" style="width: {percentage}%;" />
    </div>
  </div>
</div>

<style>
  .skillbox {
    padding: 0 30px;
  }
  .skillbox .percentage {
    float: right;
    position: relative;
    top: -40px;
    font-weight: bold;
    color: #fff;
  }
  .cover {
    width: 100%;
    height: 4px;
    background-color: #262626;
    border: 0.8px solid orange;
    border-radius: 2px;
  }
  .cover .progressbar {
    height: 3px;
    background-color: orange;
    margin-left: 0.3px;
    margin-top: 0.5px;
    border-radius: 2px;
  }
  h5 {
    font-size: 14px;
    margin-top: 8px;
    margin-bottom: 8px;
  }
</style>
