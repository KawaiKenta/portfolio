<script>
  let src = "./images/portfolio.png";
  const width = window.innerWidth;
</script>

<div class="container">
  {#if width > 768}
    <div class="image-explain"><img {src} alt="portfolio" /></div>
    <div class="text-explain">
      <h3 class="title">ポートフォリオ</h3>
      <p>
        このサイトです。次世代のフロントエンドフレームワークであるsvelteを勉強したので、実践として作成しました。
        css、javascriptの勉強も兼ねているのでjQueryやbootstrapといったフレームワークを使わず全て自力で実装してみました。
      </p>
    </div>
  {:else}
    <div class="text-explain">
      <h3 class="title">ポートフォリオ</h3>
      <p>
        このサイトです。次世代のフロントエンドフレームワークであるsvelteを勉強したので、実践として作成しました。
        css、javascriptの勉強も兼ねているのでjQueryやbootstrapといったフレームワークを使わず全て自力で実装してみました。
      </p>
    </div>
    <div class="image-explain"><img {src} alt="portfolio" /></div>
  {/if}
</div>

<style>
  .container {
    display: flex;
    margin-bottom: 48px;
  }

  h3 {
    font-size: 20px;
    margin-bottom: 8px;
  }
  img {
    width: 100%;
  }
  @media screen and (min-width: 768px) {
    .container div {
      width: 50%;
      padding: 0.8em;
    }
    .container {
      display: flex;
      margin-bottom: 48px;
    }
  }

  @media screen and (max-width: 767px) {
    .container div {
      width: 100%;
    }
    .container {
      display: flex;
      flex-direction: column;
      margin-bottom: 48px;
    }
  }
</style>
