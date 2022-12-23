<script>
  let src = "./images/portfolio.png";
</script>

<div class="container">
  <div class="image-explain"><img {src} alt="portfolio" /></div>
  <div class="text-explain">
    <h3 class="title">ポートフォリオ</h3>
    <p>
      このサイトです。次世代のフロントエンドフレームワークであるsvelteを勉強したので、実践として作成しました。
      css、javascriptの勉強も兼ねているのでjQueryやbootstrapといったフレームワークを使わず全て自力で実装してみました。
    </p>
  </div>
</div>

<style>
  .container {
    display: flex;
    margin-bottom: 48px;
  }
  .container div {
    width: 50%;
    padding: 0.8em;
  }
  h3 {
    font-size: 20px;
    margin-bottom: 8px;
  }
  img {
    width: 100%;
  }
</style>
