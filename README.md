# カロリーどれだ？ 公式サイト

GitHub Pages向けの静的サイトです。ビルド作業や依存パッケージはありません。

## ページ構成

- `index.html` — 公式トップページ
- `terms.html` — 利用規約
- `privacy.html` — プライバシーポリシー
- `disclaimer.html` — カロリー情報の免責
- `data-deletion.html` — ゲストデータの削除案内
- `support.html` — お問い合わせ
- `404.html` — ページが見つからない場合

## GitHub Pagesでの公開

HTML内のリンクは相対パスのため、ユーザーサイトとプロジェクトサイトのどちらでも動作します。

`app-ads.txt` はこのサイト用リポジトリには置きません。アプリストアに登録するデベロッパーウェブサイトと同じホストのルート、今回の場合は次のURLで表示できる必要があります。

`https://ytachiokawork-dev.github.io/app-ads.txt`

公式サイトをプロジェクトサイトのサブディレクトリで公開する場合も、`app-ads.txt` だけはユーザーサイト用リポジトリ `ytachiokawork-dev.github.io` の公開ルートへ配置してください。
