<script>
  let src = "./images/gopro.png";
</script>

<div class="container">
  <div class="text-explain">
    <h3 class="title">Go lang を用いたRESTful API</h3>
    <p>
      Go言語を用いてRESTful
      APIサーバーを作成しました。Goの有名ライブラリであるGinを使用しており、高速に動作します。JWT
      Tokenによる認証系を備えており、ユーザー登録からログイン、退会まで行えます。また設定ファイルの情報によって動作を変更でき、接続するデータベースや開放するポート、開発・リリースモード切り替えを簡単に行うことができます。
    </p>
  </div>
  <div class="image-explain"><img {src} alt="goproject" /></div>
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
