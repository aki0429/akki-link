# アッキーのちんぽ大公開 (転送リンク)

TikTok への転送リンクページ。

- 転送先: https://lite.tiktok.com/t/ZS9S7pv8fSXUG-V7NCu/
- 公開: GitHub Pages (`main` ブランチ / ルート)
- 画像: `images/` に置くとページに並びます (未配置の枠は点線プレースホルダで表示)

## 画像の追加

1. `images/` に `1.jpg`, `2.jpg` … を入れる
2. 枚数や拡張子を変えたいときは `index.html` の `IMAGES` 配列を編集

## 自動転送にする

`index.html` の `<head>` にある次の行のコメントを外すと、3秒後に自動でTikTokへ飛びます。

```html
<!-- <meta http-equiv="refresh" content="3; url=https://lite.tiktok.com/t/ZS9S7pv8fSXUG-V7NCu/"> -->
```

## タイトル変更

`index.html` の `<title>` と `<h1>` の2か所。

## 注意

- リポジトリは public なので、置いた画像はURLを知っていれば誰でも直接見られます。
- `robots` は `noindex,nofollow` にしてあります (検索結果に出さない)。
