# JOOOINT MAGAZINE

ストリート・アンダーグラウンドをテーマにした静的ウェブサイトです。HTML / CSS / JavaScriptのみで動作し、ビルドや有料サービスは不要です。

## 内容

- 雑誌紹介、NO.01〜13の表紙アーカイブ（公式ストアの掲載内容に基づく）
- 号数の絞り込み、表紙拡大、モバイルメニュー
- STORES・Instagram・Xへのリンク
- レスポンシブ対応、キーボード操作、動きを減らす設定への対応

## GitHub Pagesで公開

1. GitHubで `joooint-magazine` というPublicリポジトリを作成します。
2. このフォルダ内のファイルをリポジトリ直下へアップロードします。assetsフォルダも必須です。
3. Settings → Pages → Build and deployment → Sourceを「Deploy from a branch」に設定します。
4. Branchを `main`、フォルダを `/ (root)` にしてSaveします。
5. GitHub Pagesのビルド完了後、Settings → Pagesに表示されるURLを開きます。

## 編集

- 本文・リンク・新しい号の追加: index.html
- 色・配置・スマホ表示: style.css
- 表紙画像: assets/
- 動作: script.js

制作時点で確認できたストア掲載号を使用しています。NO.14は表紙未提供のため掲載していません。価格・在庫はサイトに固定せず、ストアで確認する構成です。問い合わせはInstagramへ誘導し、未接続の送信フォームは設置していません。

## 素材出典

表紙と各号のタイトル・クレジット: https://joooint.stores.jp/ （2026-10-09取得）
各商品の出典URLは content.json に記録しています。画像と作品の著作権は各権利者に帰属します。新しく制作したサイト本文・キャッチコピーは編集可能な初稿です。
