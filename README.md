# Leathercraft CAD Tutorials / チュートリアル

[Leathercraft CAD](https://coffee-craft.net/) のチュートリアル目次ページです。

**▶ 見る / View: https://luthierleather.github.io/tutorials/**

- 日本語 / English 切り替え、テーマ選択に対応
- 動画は [Coffee & Craft YouTube チャンネル](https://www.youtube.com/@coffee-and-craft/) で公開されています
- Leathercraft CAD 4.0 以降はアプリ内の「チュートリアル」ボタンからもこのページが開きます

## 更新方法（メンテナ向け）

`index.html` 冒頭のコメントに項目の書式と更新手順があります。要点：

1. `DATA.items` に項目・動画を追加/修正
2. 変更した項目の `updated` とページ先頭の `TUTORIAL_STAMP` を `yyyymmddhhmm` に更新
3. push（GitHub Pages に自動反映）
4. 配信索引の `tutorial=` 行を `TUTORIAL_STAMP` と同じ値に更新
   （これでアプリ側に更新バッジが出ます）
