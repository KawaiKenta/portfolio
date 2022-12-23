<script>
  const goImg = "./images/go-logo.png";
  const rustImg = "./images/rust-logo.png";
  const pythonImg = "./images/python-logo.png";
  const dartImg = "./images/dart-logo.png";
  const javaScriptImg = "./images/javascript-logo.png";
</script>

<div class="container">
  <h3>LANGUAGE</h3>
  <ul>
    <li><img src={goImg} alt="Go" /></li>
    <li><img src={rustImg} alt="Rust" /></li>
    <li><img src={pythonImg} alt="Python" /></li>
    <li><img src={dartImg} alt="Dart" /></li>
    <li><img src={javaScriptImg} alt="JavaScript" /></li>
  </ul>
</div>

<style>
  ul {
    display: flex;
    align-items: center;
    justify-content: center;
    padding-left: 0px;
  }
  li {
    list-style: none;
    width: 100%;
  }
  li img {
    display: block;
    margin: auto;
    max-width: 70%;
  }
  h3 {
    font-size: 20px;
    margin-bottom: 8px;
  }
  .container {
    padding: 0.8em;
  }
</style>
