# FINSカレンダー

仲良し4世帯（藤﨑家・長野家・下田家・伊藤家）の遊び日程を合わせるアプリの画面。

- 公開先: https://teraco-labo.github.io/fins/
- データはGoogle Apps Script（スプレッドシート）側に保存される
- 画面のソースは別リポジトリ（family-scheduler/src/Index.html）で管理し、
  `node tools/build-web.js` で生成したものをここに置いている

GASのWebアプリURLを直接配らない理由: 端末のGoogleログイン状態によっては
「ファイルを開くことができません」と出て開けないため。静的サイトなら誰でも開ける。
